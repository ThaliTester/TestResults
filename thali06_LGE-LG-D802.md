#### Test 568182548138a64_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/GAV2    ( 4627): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  950): Killing 4063:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{4336a958 stackId=1, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2}
,D/dalvikvm( 1967): GC_CONCURRENT freed 1666K, 23% free 19352K/24832K, paused 3ms+4ms, total 40ms
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/ConfigFetchService( 1967): fetch service done; releasing wakelock
I/ConfigFetchService( 1967): stopping self
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1967): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4678): 
D/AndroidRuntime( 4678): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4678): CheckJNI is OFF
D/dalvikvm( 4678): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4678): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4678): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4678): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4678): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4678): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1967): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1967): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1967): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4678): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4678): failed to load memtrack module: -2
D/AndroidRuntime( 4678): Calling main entry com.android.commands.am.Am
I/ActivityManager(  950): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4678
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{4336a958 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (154 us)
V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm(  950): GC_FOR_ALLOC freed 24149K, 54% free 28039K/59908K, paused 121ms, total 121ms
D/WifiStateMachine(  950): handleMessage: E msg.what=131155
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
D/ActivityManager(  950): resumeTopActivityLocked: Pausing null
V/ActivityManager(  950): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  950): setFocusedStack: mFocusedStack=ActivityStack{4336a958 stackId=1, 2 tasks}
I/ActivityManager(  950): startService SlideAside
W/ContextImpl(  950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  950): handleMessage: X
D/AndroidRuntime( 4678): Shutting down VM
D/UsbSettingsControl( 2589): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2589): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  950): allPausedActivitiesComplete: r=ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{4336a958 stackId=1, 2 tasks}
I/SlideAside( 4041): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4678): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
D/ActivityManager(  950): resumeTopActivityLocked: Restarting ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  950): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4692 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  950): Moving to RESUMED: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+2ms, total 24ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 15ms
D/HyLog   ( 4692): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4692): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4692): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 15ms
I/SlideAside( 4041): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4041): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4692): Binding Chromium to the background looper Looper (main, tid 1) {428c7df0}
I/chromium( 4692): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4692): Initializing chromium process, renderers=0
W/chromium( 4692): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4692): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4692): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4692): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4692): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4692): Remote Branch: 
I/Adreno-EGL( 4692): Local Patches: 
I/Adreno-EGL( 4692): Reconstruct Branch: 
I/dalvikvm( 4692): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4692): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4692): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4692): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4692): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4692): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4692): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4692): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4692): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4692): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4692): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4692): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4692): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4692): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4692): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4692): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4692): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4692): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4692): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4692): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  950): battery changed pluggedType: 2
,W/BaseRuntimeLoader( 4692): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4692): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4692): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4692): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/OpenGLRenderer( 4692): Enabling debug mode 0
,W/AwContents( 4692): nativeOnDraw failed; clearing to background color.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/InputMethodManagerService(  950): IME STATUS OFF
W/AwContents( 4692): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  950): Displayed com.test.thalitest/.MainActivity: +443ms
,I/ActivityManager( 4692): Timeline: Activity_idle id: android.os.BinderProxy@428c95c0 time:112235
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/JsMessageQueue( 4692): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4692): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428cd790
,D/dalvikvm( 4692): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428cd790
,D/jxcore_app_log( 4692): JniHelper::setJavaVM(0x4178a838), pthread_self() = 1633075208
,I/chromium( 4692): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  950): Timeline: Activity_windows_visible id: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3} time:112552
D/ActivityManager(  950): no-history finish of ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  950): Finishing activity token=Token{433696a8 ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  950): Moving to FINISHING: ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2 f}
,D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,I/chromium( 4692): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/UsbSettings( 2589): [AUTORUN] onStop()
I/chromium( 4692): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  950): Moving to STOPPED: ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.460419 Y: -0.417450 Z: 9.799408 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460419 .y:-0.417450 .z:9.799408
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.460159 Y: -0.419235 Z: 9.779724 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460159 .y:-0.419235 .z:9.779724
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
D/dalvikvm( 4692): GC_CONCURRENT freed 2643K, 12% free 22009K/24832K, paused 3ms+4ms, total 57ms
D/dalvikvm( 4692): WAIT_FOR_CONCURRENT_GC blocked 46ms
D/dalvikvm( 4692): WAIT_FOR_CONCURRENT_GC blocked 42ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4692): GC_FOR_ALLOC freed 414K, 10% free 22358K/24832K, paused 36ms, total 36ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
D/dalvikvm( 4692): GC_FOR_ALLOC freed 104K, 10% free 22365K/24832K, paused 26ms, total 28ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 24.076MB for 63974-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  950): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4692): GC_FOR_ALLOC freed 126K, 11% free 22385K/24896K, paused 32ms, total 32ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 24.125MB for 95956-byte allocation
D/dalvikvm( 4692): GC_FOR_ALLOC freed 179K, 11% free 22420K/24992K, paused 27ms, total 27ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 24.206MB for 143930-byte allocation
D/dalvikvm( 4692): GC_FOR_ALLOC freed 254K, 11% free 22467K/25136K, paused 27ms, total 27ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 24.320MB for 215890-byte allocation
D/dalvikvm( 4692): GC_FOR_ALLOC freed 366K, 12% free 22541K/25348K, paused 25ms, total 25ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 24.496MB for 323830-byte allocation
D/dalvikvm( 4692): GC_FOR_ALLOC freed 567K, 12% free 22661K/25668K, paused 27ms, total 28ms
D/dalvikvm( 4692): GC_FOR_ALLOC freed 860K, 12% free 22838K/25668K, paused 24ms, total 24ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 25.170MB for 728606-byte allocation
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/dalvikvm( 4692): GC_FOR_ALLOC freed 1280K, 13% free 23093K/26380K, paused 39ms, total 39ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 25.768MB for 1092904-byte allocation
D/dalvikvm( 4692): GC_CONCURRENT freed 1862K, 15% free 23505K/27448K, paused 0ms+2ms, total 33ms
D/dalvikvm( 4692): GC_FOR_ALLOC freed 200K, 15% free 23394K/27448K, paused 24ms, total 25ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 26.583MB for 1639352-byte allocation
D/dalvikvm( 4692): GC_CONCURRENT freed 1816K, 18% free 24002K/29052K, paused 1ms+1ms, total 31ms
D/dalvikvm( 4692): GC_FOR_ALLOC freed 1075K, 18% free 23992K/29052K, paused 26ms, total 26ms
I/dalvikvm-heap( 4692): Grow heap (frag case) to 27.949MB for 2459024-byte allocation
D/dalvikvm( 4692): GC_CONCURRENT freed 1827K, 22% free 24805K/31456K, paused 2ms+3ms, total 34ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4692): GC_CONCURRENT freed 2565K, 21% free 25021K/31456K, paused 2ms+4ms, total 40ms
D/dalvikvm( 4692): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4692): GC_FOR_ALLOC freed 312K, 22% free 24820K/31456K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4692): Grow heap (frag case) to 29.929MB for 3688532-byte allocation
,D/dalvikvm( 4692): GC_CONCURRENT freed 218K, 10% free 28335K/31456K, paused 4ms+2ms, total 32ms
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/dalvikvm( 4692): GC_FOR_ALLOC freed 4326K, 10% free 26143K/28856K, paused 28ms, total 30ms
,I/dalvikvm-heap( 4692): Grow heap (frag case) to 30.612MB for 3049686-byte allocation
,W/jxcore-log( 4692): Initializing JXcore engine
,W/jxcore-log( 4692): JXcore engine is ready
,D/dalvikvm( 4692): GC_CONCURRENT freed 529K, 10% free 28965K/31836K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 4692): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4692): Starting JXcore engine
,W/jxcore-log( 4692): Platform android
W/jxcore-log( 4692): 
,W/jxcore-log( 4692): Process ARCH arm
W/jxcore-log( 4692): 
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  950): battery changed pluggedType: 2
,I/jxcore-log( 4692): JXcore Cordova bridge is ready!
I/jxcore-log( 4692): 
,W/jxcore-log( 4692): JXcore engine is started
,E/jxcore  ( 4692): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4692): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4692): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  950): Finishing activity token=Token{442a9ac0 ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  950): GC_FOR_ALLOC freed 1120K, 51% free 29625K/59908K, paused 75ms, total 75ms
,W/PluginManager( 4692): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 87ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{4336a958 stackId=1, 2 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  950): moveHomeStack:
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
V/ActivityManager(  950): Moving to RESUMED: ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  950): resumeTopActivityLocked: Resumed ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  950): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1491): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1491): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1451): getIsInUseVoLTE : false
I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1491): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1491): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1840): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 23:40:39
,I/[LGHome]EVENT( 1491): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/IInputConnectionWrapper( 4692): showStatusIcon on inactive InputConnection
I/InputMethodManagerService(  950): IME STATUS OFF
,D/UpdateThreadPoolManager( 1840): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
D/WeatherService( 1840): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1840): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1840): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1840): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1840): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1840): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 23:40:39
D/WeatherService( 1840): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
D/Weather.Utils( 1840): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1840): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1840): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1840): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1840): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1840): 2 : This is isUpdating : false
D/WeatherService( 1840): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1840): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1840): 2 : Map key string is -2
D/lim     ( 1840): 2 : time = 23:40
I/WeatherReflect( 1840): Model Name : LG-D802
D/WeatherTheme( 1840): 2 : Different view - status_min_formatted : 39 != 40
D/WeatherTheme( 1840): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1840): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1840): 2 : Fixed theme : optimus
D/WeatherTheme( 1840): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1840): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1840): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1491): GC_CONCURRENT freed 5533K, 9% free 60928K/66648K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 1491): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 1145): GC_FOR_ALLOC freed 3681K, 7% free 71473K/76544K, paused 38ms, total 43ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1491): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1491): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1491): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1491): GC_FOR_ALLOC freed 4871K, 9% free 61906K/67488K, paused 18ms, total 18ms
,I/GAV2    ( 4627): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@428c2fa0 time:115732
,D/UsbSettings( 2589): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2589): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2589): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2589): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  950): Moving to DESTROYING: ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  950): Moving to DESTROYED: ActivityRecord{43369540 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  950): Timeline: Activity_windows_visible id: ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1} time:115784
,E/libEGL  ( 4692): call to OpenGL ES API with no current context (logged once per thread)
V/ActivityManager(  950): Moving to FINISHING: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  950): Killing 4158:com.google.android.talk/u0a77 (adj 15): empty #17
V/ActivityManager(  950): Moving to DESTROYING: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
V/ActivityManager(  950): Moving to DESTROYED: ActivityRecord{43b6c1d8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Top activity resumed ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  950): battery changed pluggedType: 2
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/ConfigService( 1538): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  950): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  950): battery changed pluggedType: 2
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  950): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1491): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1491): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,E/[LGHome]NumberBadge( 1491): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
,D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.464111 Y: -0.416153 Z: 9.768860 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464111 .y:-0.416153 .z:9.768860
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.459244 Y: -0.422195 Z: 9.761002 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459244 .y:-0.422195 .z:9.761002
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4245): [399] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4245): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  950): battery changed pluggedType: 2
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/WifiController(  950): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
,D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416060077, nextTick: 59951, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416060082, nextTick: 59951, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1840): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:41:0
,D/WeatherService( 1840): 2 : TimeTick Intent And Screen On
D/WeatherService( 1840): 2 : SDK version : 19
,D/WeatherQuickCover( 1840): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1840): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1840): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1840): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1840): 2 : This is isUpdating : false
D/WeatherService( 1840): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1840): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1840): 2 : Map key string is -2
,D/lim     ( 1840): 2 : time = 23:41
I/WeatherReflect( 1840): Model Name : LG-D802
D/WeatherTheme( 1840): 2 : Different view - status_min_formatted : 40 != 41
,D/WeatherTheme( 1840): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1840): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1840): 2 : Fixed theme : optimus
,D/WeatherTheme( 1840): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1840): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:41:0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/PowerManagerService(  950): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  950): [updateScreenState] screen on = false
D/KnockOnPowerController(  950): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  950): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  950): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  950): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  950): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/KnockOnPowerController(  950): [setProximitySensorEnabled] enable = true
D/qcom_sensors_hal(  950): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8163 usec
,D/qcom_sensors_hal(  950): hal_acquire_resources
,I/qcom_sensors_hal(  950): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  950): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  950): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  950): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  950): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  950): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  950): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  950): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.457123 Y: -0.422836 Z: 9.792389 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457123 .y:-0.422836 .z:9.792389
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.445831 Y: -0.411209 Z: 9.796188 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445831 .y:-0.411209 .z:9.796188
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,I/Sensors (  323): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  950): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  950): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  950): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  950): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  950): proximitySensorChanged  positive = true
I/KnockOnPowerController(  950): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.461914 Y: -0.415100 Z: 9.793259 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461914 .y:-0.415100 .z:9.793259
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.458054 Y: -0.396957 Z: 9.792587 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458054 .y:-0.396957 .z:9.792587
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0,
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.443283 Y: -0.394974 Z: 9.797852 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443283 .y:-0.394974 .z:9.797852
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.442307 Y: -0.411072 Z: 9.802490 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442307 .y:-0.411072 .z:9.802490
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7546450
,V/KeyguardServiceDelegate(  950): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43beef78)
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1145): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1145): notifyScreenOnLocked
,D/KeyguardViewMediator( 1145): handleNotifyScreenOn
,D/KeyguardViewManager( 1145): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  950): **** SHOWN CALLED ****
,I/WindowManager(  950): No lock screen! windowToken=null
D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.456345 Y: -0.414017 Z: 9.797516 
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456345 .y:-0.414017 .z:9.797516
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,E/SlideAside( 4041): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  950): handleScreenStateChanged: true
,D/WifiStateMachine(  950): handleMessage: E msg.what=131154
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  950): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  950): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131127
D/WifiStateMachine(  950): processMsg: ConnectedState
,D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131158
,D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
D/WifiStateMachine(  950): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  950): handleMessage: X
,D/WifiStateMachine(  950): handleMessage: E msg.what=132097
,D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
,D/WifiStateMachine(  950): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  950): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2023): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  950): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  950): stopMonitoring
,E/AudioSystem(  950): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 950
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
,V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1159): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433ea5b8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1159): enqueuing start. mLedList.size()=2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1159): enqueuing end. mLedList.size()=3
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,I/SlideAside( 4041): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1840): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 23:41:2
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1840): 2 : This is isUpdating : false
,D/WeatherAncestor( 1840): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 23:41:2
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/WeatherService( 1840): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1840): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1159): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1159): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1159): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1159): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1159): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  950): Excessive delay in blankDisplay() while turning screen off: 413ms
,D/qdlights( 1159): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1159): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1159): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 201, B = 201
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.450287 Y: -0.411560 Z: 9.795456 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450287 .y:-0.411560 .z:9.795456
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,D/qdlights( 1159): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1159): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1159): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1159): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1159): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1159): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 165, B = 165
,D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
,V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  950): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  950): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  950): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  950): hal_process_report_ind: X: -0.460037 Y: -0.421463 Z: 9.792648 
D/qcom_sensors_hal(  950): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460037 .y:-0.421463 .z:9.792648
,D/qcom_sensors_hal(  950): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=0
,D/qdlights( 1159): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416062925, nextTick: 57106, mDrawingTime: 1
,D/qdlights( 1159): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1159): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1159): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1159): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 135, B = 135
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416062967, nextTick: 57065, mDrawingTime: 0
,D/qdlights( 1159): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 129, B = 129
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/qdlights( 1159): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1159): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 117, B = 117
,D/WeatherService( 1840): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:41:3
,D/WeatherService( 1840): 2 : ACTION screen on
,D/WeatherService( 1840): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1840): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:41:3
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1159): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 111, B = 111
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1159): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 105, B = 105
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  950): ACTION_SCREEN_ON
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  950): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  950): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  950): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1145): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1145): notifyScreenOffLocked
D/WifiStateMachine(  950): handleMessage: E msg.what=131155
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): handleMessage: X
I/[LGHome]EVENT( 1491): [Launcher.java:894:onPause()]onPause
D/qdlights( 1159): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 99, B = 99
V/ActivityManager(  950): Moving to PAUSING: ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1}
D/qcom_sensors_hal(  950): hal_acquire_resources
D/qcom_sensors_hal(  950): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  950): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  950): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  950): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  950): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  950): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  950): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1159): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 93, B = 93
D/KeyguardViewMediator( 1145): setting alarm to turn off keyguard, seq = 2, timeout = 5000
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  950): Moving to PAUSED: ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  950): Moving to STOPPING: ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/qdlights( 1159): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 87, B = 87
I/[LGHome]EVENT( 1491): [Launcher.java:4955:onStop()]onStop
D/KeyguardViewMediator( 1145): handleNotifyScreenOff
D/KeyguardViewManager( 1145): onScreenTurnedOff()
I/LGImmersionVibrator(  950): Vibrator off
D/WifiStateMachine(  950): handleScreenStateChanged: false
D/WifiStateMachine(  950): handleMessage: E msg.what=131154
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131158
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
D/WifiStateMachine(  950): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  950): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  950): Moving to STOPPED: ActivityRecord{432cc5d0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/qdlights( 1159): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 81, B = 81
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  950): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 950
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiController(  950): CMD_SCREEN_OFF 
D/WifiController(  950): shouldWifiStayAwake TRUE
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1159): clear
E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1159): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 75, B = 75
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
,D/WifiNative-wlan0(  950):    returned true
,D/WifiStateMachine(  950): handleMessage: X
,I/[LGHome]EVENT( 1491): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1159): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 69, B = 69
D/WeatherService( 1840): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:41:3
,D/WeatherService( 1840): 2 : ACTION screen off
,D/WeatherService( 1840): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:41:3
,V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
,E/Parcel  (  607): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/qdlights( 1159): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 63, B = 63
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1451): Emergency Service
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
D/qdlights( 1159): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 57, B = 57
,D/NfcService( 1477): NFC-C OFF
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  950): ACTION_SCREEN_OFF
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/qdlights( 1159): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1159): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1159): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1159): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1159): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1159): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1159): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  323): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  950): handleMessage: E msg.what=131155
,D/WifiStateMachine(  950): processMsg: ConnectedState
,D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiStateMachine(  950): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1145): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1145): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/KeyguardViewMediator( 1145): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1145): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416080813733231; DSPS: 5275245; Offset: 1453415919826031815
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  950): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416100815029578; DSPS: 5930647; Offset: 1453415919826046424
,I/rmt_storage(  618): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb7177178
I/rmt_storage(  618): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  618): wakelock acquired: 1, error no: 42
,I/rmt_storage(  618): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1223200200)
,I/rmt_storage(  618): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  618): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  618): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1223200200) wakelock released: 1, error no: 0
I/rmt_storage(  618): 
I/rmt_storage(  618): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb7177178
,E/Diag_Lib(  700): [IMS_FATAL]| 2912 | 708 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416120031, nextTick: 60000, mDrawingTime: 1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416120051, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416120816937904; DSPS: 6586070; Offset: 1453415919826032143
,W/ProcessCpuTracker(  950): Skipping unknown process pid 4937
,W/ProcessCpuTracker(  950): Skipping unknown process pid 4940
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1538): Using platform SSLCertificateSocketFactory
,I/VacuumService( 1538): Vacuum at: now=1453416125582 tag=VacuumService
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1538): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1538): No account for auth token provided
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1538): No account for auth token provided
,W/Uploader( 1538):  no longer exists, so no auth token.
,W/Uploader( 1538): No account for auth token provided
,W/Uploader( 1538): No account for auth token provided
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 4 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:26:f2:18:08:c8]
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416140818290813; DSPS: 7241474; Offset: 1453415919826042278
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416160819574503; DSPS: 7896876; Offset: 1453415919826044230
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/WifiController(  950): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416180051, nextTick: 59977, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416180054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416180820920381; DSPS: 8552280; Offset: 1453415919826047335
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416200822205894; DSPS: 9207682; Offset: 1453415919826051109
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416220823499532; DSPS: 9863085; Offset: 1453415919826032491
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416240054, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416240058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416240824827179; DSPS: 10518488; Offset: 1453415919826047883
,D/dalvikvm( 2643): GC_CONCURRENT freed 7783K, 33% free 16860K/24832K, paused 2ms+1ms, total 34ms
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x428f6588: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4245): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4245): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4245): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4245): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4245): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4245): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4245): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4245): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4245): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4245): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416260826155037; DSPS: 11173892; Offset: 1453415919826032967
,I/LocationManagerService(  950): remove 4325cf50
,D/LocationManagerService(  950): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  950): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  950): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  950): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  950): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2643): GC_FOR_ALLOC freed 1707K, 32% free 17069K/24832K, paused 22ms, total 23ms
,D/dalvikvm( 2643): GC_CONCURRENT freed 1812K, 31% free 17304K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2643): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Mlt MonitorService( 2643): parseLastkmsg to dump
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416280828044874; DSPS: 11829314; Offset: 1453415919826030714
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416300033, nextTick: 59993, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416300037, nextTick: 59995, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416300829372470; DSPS: 12484717; Offset: 1453415919826046054
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416320830372931; DSPS: 13140110; Offset: 1453415919826039435
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416340831881672; DSPS: 13795519; Offset: 1453415919826052815
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416360037, nextTick: 59992, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416360039, nextTick: 59993, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416360833206510; DSPS: 14450923; Offset: 1453415919826034880
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416380834486033; DSPS: 15106325; Offset: 1453415919826032664
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416400834905661; DSPS: 15761698; Offset: 1453415919826055564
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416420069, nextTick: 59962, mDrawingTime: 1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416420071, nextTick: 59961, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416420836057737; DSPS: 16417096; Offset: 1453415919826047972
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416440837945073; DSPS: 17072518; Offset: 1453415919826043218
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416460839202774; DSPS: 17727919; Offset: 1453415919826049698
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416480033, nextTick: 59998, mDrawingTime: 1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416480035, nextTick: 59998, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416480840546256; DSPS: 18383323; Offset: 1453415919826050407
,W/ProcessCpuTracker(  950): Skipping unknown process pid 5306
,W/ProcessCpuTracker(  950): Skipping unknown process pid 5309
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416500841843904; DSPS: 19038726; Offset: 1453415919826035799
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416520843119001; DSPS: 19694127; Offset: 1453415919826059675
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416540039, nextTick: 59991, mDrawingTime: 1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416540042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416540844441076; DSPS: 20349531; Offset: 1453415919826038977
,I/ActivityManager(  950): Killing 3886:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416560845329662; DSPS: 21004920; Offset: 1453415919826042553
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416580847156270; DSPS: 21660340; Offset: 1453415919826038106
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416600041, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416600047, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416600848187825; DSPS: 22315733; Offset: 1453415919826062581
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416620849150420; DSPS: 22971125; Offset: 1453415919826048614
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416640850013173; DSPS: 23626513; Offset: 1453415919826056875
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416660039, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416660044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416660850898843; DSPS: 24281902; Offset: 1453415919826057535
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416680851327273; DSPS: 24937276; Offset: 1453415919826058719
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416700852205181; DSPS: 25592665; Offset: 1453415919826051617
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  950): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416720034, nextTick: 59968, mDrawingTime: 11
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416720058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416720853579600; DSPS: 26248070; Offset: 1453415919826052745
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416740854434489; DSPS: 26903458; Offset: 1453415919826053142
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416760854881096; DSPS: 27558833; Offset: 1453415919826041985
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416780040, nextTick: 59985, mDrawingTime: 6
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416780043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416780859079736; DSPS: 28214330; Offset: 1453415919826059717
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Disconnect event
D/wpa_supplicant( 2023): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2023): wlan0: Deauthentication notification
D/wpa_supplicant( 2023): wlan0:  * reason 0
D/wpa_supplicant( 2023): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2023): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2023): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2023): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
,D/WifiStateMachine(  950): handleMessage: E msg.what=147460,
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb83edd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2023): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state INITIALIZE,
,D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): Network connection lost
D/WifiStateMachine(  950): Stopping DHCP and clearing IP
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  950): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  950): doBoolean: SET ps 1
,D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  950):    returned true
D/WifiNative-wlan0(  950): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  950): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  950): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  950):    returned true
D/DhcpStateMachine(  950): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  950): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  950): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  950): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2023): wlan0: nl80211: scan request
,D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: Scan trigger
,D/ConnectivityServiceHSM(  950): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/WifiHS20(  950): hidePasspointNotification off =false
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
D/QCNEA   (  607): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  607): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  607): |CAC| updateNetCfgInfo
V/QCNEA   (  607): |CAC| *********************************************
V/QCNEA   (  607): |CAC|                   Netconfig               
V/QCNEA   (  607): |CAC| *********************************************
V/QCNEA   (  607): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  607): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  607): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  607): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  607): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  607): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  607): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  607): |CAC| *********************************************
D/QCNEA   (  607): |CAC| Received bssid= 
D/QCNEA   (  607): |CAC| net type = 3
V/QCNEA   (  607): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  607): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  607): |CAC| 	ssid           =NG700
V/QCNEA   (  607): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  607): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  607): |CAC| *********************************************
D/QCNEA   (  607): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  607): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  607): |CAC| dispatchNetCfg: updating:0xb877e8dc
,D/QCNEA   (  607): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  607): Reading a NULL string not supported here.
,E/Parcel  (  607): Reading a NULL string not supported here.
D/QcConnectivityService(  950): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  950): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  950): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  950): handleMessage: new destination call exit/enter
D/QcConnectivityService(  950): Attempting to switch to mobile
D/QcConnectivityService(  950): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  950): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  950): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  950): invokeExitMethods: ConnectedState
D/WifiStateMachine(  950): invokeExitMethods: L2ConnectedState
D/NetworkManagementService(  950): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  950): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  950): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  950): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/NetworkManagementService(  950): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131213
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
D/WifiStateMachine(  950): processMsg: DriverStartedStateExt
D/WifiStateMachine(  950): processMsg: SupplicantStartedState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131213
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
D/WifiStateMachine(  950): processMsg: DriverStartedStateExt
D/NetworkManagementService(  950): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  950): processMsg: SupplicantStartedState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  950): processMsg: ConnectModeState
V/        (  264): RouteController
D/WifiStateMachine(  950): handleMessage: X
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  950): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5611 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
W/NetworkManagementService(  950): route cmd failed: 
W/NetworkManagementService(  950): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  950): '
W/NetworkManagementService(  950): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  950): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  950): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  950): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  950): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  950): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  950): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  950): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  950): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  950): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  950): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  950): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  950): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  950): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  950): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  950): android_net_utils_resetConnections in env=0x6186de10 clazz=0x62200001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1538): Read error: ssl=0x612d9190: I/O error during system call, Connection timed out
,V/NativeCrypto( 1538): SSL shutdown failed: ssl=0x612d9190: I/O error during system call, Broken pipe
D/QcConnectivityService(  950): resetConnections(wlan0, 3)
,D/HyLog   ( 5611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5611): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 2643): GC_CONCURRENT freed 2500K, 33% free 16750K/24832K, paused 4ms+2ms, total 42ms
,I/PCSuite ( 5611): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5611): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5611): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/DhcpStateMachine(  950): StoppedState
I/ActivityManager(  950): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5632 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  950): Killing 2135:android.process.media/u0a23 (adj 15): empty #17
D/Nat464Xlat(  950): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  950): Sampling interval elapsed, updating statistics ..
,D/LocSvc_java(  950): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  950): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  950): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  950): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5632): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5632): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5632): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  950): Done.
D/QcConnectivityService(  950): Setting timer for 720seconds
D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 5632): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 5632): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 5632): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5632): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 5632): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5632): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5632): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5632): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5632): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  950): Killing 4310:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  950): GC_CONCURRENT freed 2251K, 49% free 30619K/59908K, paused 4ms+8ms, total 126ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  950): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  950): MasterInitialState.processMessage what=3
,D/QcConnectivityService(  950): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null,
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2023): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 5 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 7 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 8 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 9 BSSID e8:40:f2:d6:e0:6b SSID 'WDA83'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 10 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 11 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=8/32 last_scan_full=0,
D/wpa_supplicant( 2023): wlan0: New scan results available
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2023): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2023): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
,D/wpa_supplicant( 2023): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2023): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2023): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2023): wlan0: 2: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-80
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 2023): wlan0: 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-86 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 5: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 caps=0x411 level=-89
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2023): wlan0: 6: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-89 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 7: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 caps=0x1411 level=-89 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2023): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2023): wlan0:    selected based on RSN IE
,D/wpa_supplicant( 2023): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700',
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83ef5a8  current_ssid=0x0
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 38:f8:89:11:e9:11]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 e8:40:f2:d6:e0:6b]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 64:7c:34:12:7f:81]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 a0:c5:62:7a:49:96]
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): TDLS: TDLS is allowed in the target BSS,
I/wpa_supplicant( 2023): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2023): wlan0: Cancelling scan request,
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2023): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2023): RSN: PMKSA cache search - network_ctx=0xb83ef5a8 try_opportunistic=0
D/wpa_supplicant( 2023): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2023): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2023): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: WPA: using GTK CCMP
,D/wpa_supplicant( 2023): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using KEY_MGMT WPA-PSK,
D/wpa_supplicant( 2023): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
,D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb83ee590 (mode change)
D/wpa_supplicant( 2023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0a,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0e,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb83ee590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2023): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2023):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023):   * freq=2412
D/wpa_supplicant( 2023):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2023):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2023):   * Auth Type 0
D/wpa_supplicant( 2023):   * WPA Versions 0x2
D/wpa_supplicant( 2023): nl80211: Connect request send successfully
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Connect event
D/wpa_supplicant( 2023): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2023): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2023): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2023): wlan0: Association info event
D/wpa_supplicant( 2023): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2023): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): wlan0: freq=2412 MHz
D/wpa_supplicant( 2023): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2023): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2023): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2023): TDLS: Remove peers on association
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2023): EAPOL: enable timer tick
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
,D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  950): handleMessage: E msg.what=147461
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
D/WifiStateMachine(  950): processMsg: DriverStartedStateExt
D/WifiStateMachine(  950): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  950): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2023): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 6a a6 89 e9 99 04 5e 0a b6 e0 43 3f 39 7d 6e ...
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 6a a6 89 e9 99 04 5e 0a b6 e0 43 3f 39 7d 6e a5 67 45 80 ea bc 17 7a eb b5 ac 11 7e b6 25 04 8b
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 6a a6 89 e9 99 04 5e 0a b6 e0 43 3f 39 7d 6e ...
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2023): Get randomness: len=32 entropy=9
D/wpa_supplicant( 2023): WPA: Renewed SNonce - hexdump(len=32): 1e e3 41 ff de fc b0 c0 a7 78 f7 93 f4 c2 c6 71 20 19 9d b7 ec b3 4d c7 53 dc d3 a1 ca ac d6 db
D/wpa_supplicant( 2023): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): WPA: Nonce1 - hexdump(len=32): 1e e3 41 ff de fc b0 c0 a7 78 f7 93 f4 c2 c6 71 20 19 9d b7 ec b3 4d c7 53 dc d3 a1 ca ac d6 db
D/wpa_supplicant( 2023): WPA: Nonce2 - hexdump(len=32): 6a a6 89 e9 99 04 5e 0a b6 e0 43 3f 39 7d 6e a5 67 45 80 ea bc 17 7a eb b5 ac 11 7e b6 25 04 8b
D/wpa_supplicant( 2023): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2023): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): e5 fc 7c f4 26 50 e2 b2 0d 1b 32 d1 ce 28 83 69
D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 1e e3 41 ff de fc b0 c0 a7 78 f7 93 f4 c2 c6 ...
,D/WifiMonitor(  950): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 6a a6 89 e9 99 04 5e 0a b6 e0 43 3f 39 7d 6e ...
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 6a a6 89 e9 99 04 5e 0a b6 e0 43 3f 39 7d 6e a5 67 45 80 ea bc 17 7a eb b5 ac 11 7e b6 25 04 8b
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 78 7b 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 3e 66 9f 4b 81 56 0f ef aa 5c 1c a7 9f 07 94 55
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 6a a6 89 e9 99 04 5e 0a b6 e0 43 3f 39 7d 6e ...
D/wpa_supplicant( 2023): RSN: encrypted key data - hexdump(len=56): e3 e3 f4 ce 8d 0a dd de c5 93 18 a5 7b 1c 9c 4c f6 0a c8 68 84 b5 29 e0 85 da 05 de 8b 09 53 af ...
D/wpa_supplicant( 2023): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 73 0b ...
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): fe 9b 25 7a 67 d1 74 8f cf a1 c7 49 c5 fb 5d e3
D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb83eec54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
W/WifiMonitor(  950): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2023): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2023): WPA: RSC - hexdump(len=6): 78 7b 00 00 00 00
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f0e03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2023):    broadcast key
I/wpa_supplicant( 2023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2023): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): EAPOL authentication completed successfully
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  950): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  950): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  950): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  950): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/WifiStateMachine(  950): handleMessage: X
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=147459
D/WifiStateMachine(  950): processMsg: DisconnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): Network connection established
,D/WifiNative-wlan0(  950): doString: STATUS
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2023): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  950):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  950): ssid=NG700
D/WifiNative-wlan0(  950): id=0
D/WifiNative-wlan0(  950): mode=station
D/WifiNative-wlan0(  950): pairwise_cipher=CCMP
D/WifiNative-wlan0(  950): group_cipher=CCMP
D/WifiNative-wlan0(  950): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  950): wpa_state=COMPLETED
D/WifiNative-wlan0(  950): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  950): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  950): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  950): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  950): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  950): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  950): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  950): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  950): handleMessage: new destination call exit/enter
D/WifiStateMachine(  950): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  950): invokeExitMethods: DisconnectedState
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  950): moveTempStackToStateStack: i=1,j=5
,D/WifiStateMachine(  950): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  950): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  950): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  950): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  950): handleMessage: X
D/DhcpStateMachine(  950): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/DhcpStateMachine(  950): WaitBeforeStartState
,D/WifiStateMachine(  950): processMsg: ObtainingIpState
I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
D/WifiStateMachine(  950): ObtainingIpState{ when=-63ms what=147462 obj=android.net.wifi.StateChangeResult@42ccc270 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  950): processMsg: L2ConnectedState
I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] connect :false
D/WifiStateMachine(  950): processMsg: ConnectModeState
,D/WifiStateMachine(  950): handleMessage: X
,I/AppUp4:CustModeStarterReceiver( 4017): onReceive
,D/WifiStateMachine(  950): handleMessage: E msg.what=147462
D/WifiStateMachine(  950): processMsg: ObtainingIpState
D/WifiStateMachine(  950): ObtainingIpState{ when=-50ms what=147462 obj=android.net.wifi.StateChangeResult@42c99378 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiStateMachine(  950): processMsg: ConnectModeState
D/AppUp4:CustFacade( 4017): Context : android.app.ReceiverRestrictedContext@428da050
D/WifiStateMachine(  950): handleMessage: X
D/AppUp4:CustFacade( 4017): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4017): isOpenOperator : true
D/AppUp4:CustFacade( 4017): isPhone : true
D/WifiStateMachine(  950): handleMessage: E msg.what=147459
,D/WifiStateMachine(  950): processMsg: ObtainingIpState
D/WifiStateMachine(  950): ObtainingIpState{ when=-50ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  950): processMsg: L2ConnectedState
I/LicenseContentProvider( 3021): start selecting data
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=196612
,D/WifiStateMachine(  950): processMsg: ObtainingIpState
D/WifiStateMachine(  950): ObtainingIpState{ when=-10ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/SIMObserver( 3021): simInfo1
,D/WifiNative-wlan0(  950): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/AppUp4:EulaManager( 4017): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4017): begin check event
,I/AppUp4:CustModeStarterReceiver( 4017): Event For GoodConnectivity
,I/ActivityManager(  950): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5680 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5680): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5680): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5680): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  950):    returned true
D/WifiStateMachine(  950): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  950): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  950):    returned true
,D/WifiNative-wlan0(  950): doBoolean: SET ps 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  950):    returned true
D/WifiNative-wlan0(  950): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  950):    returned null
E/WifiStateMachine(  950): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  950): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  950):    returned null
,E/WifiStateMachine(  950): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  950): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  950): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  950): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  950): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
D/WifiP2pService(  950): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433f6d30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  950): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@433f6d30 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  950): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  950): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=131212
D/WifiStateMachine(  950): processMsg: ObtainingIpState
D/WifiStateMachine(  950): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
D/WifiStateMachine(  950): processMsg: DriverStartedStateExt
D/WifiStateMachine(  950): processMsg: SupplicantStartedState
D/WifiStateMachine(  950): processMsg: DefaultState
D/WifiStateMachine(  950): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  950): handleMessage: X
D/WifiStateMachine(  950): handleMessage: E msg.what=196613
D/WifiStateMachine(  950): processMsg: ObtainingIpState
D/WifiStateMachine(  950): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  950): processMsg: L2ConnectedState
D/WifiStateMachine(  950): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  950): doBoolean: DRIVER SETSUSPENDMODE 1
V/DownloadManager( 5680): DownloadService onCreate
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/EAS     ( 4609): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4609): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  950):    returned true
D/WifiNative-wlan0(  950): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
I/DownloadManager( 5680): in removeSpuriousFiles
D/WifiNative-wlan0(  950):    returned true
D/WifiNative-wlan0(  950): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/eas_req ( 4609): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/WifiP2pService(  950): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  950): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  950):    returned true
D/WifiStateMachine(  950): DHCP successful
V/DownloadManager( 5680): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WifiStateMachine(  950): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  950): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  950): handleMessage: new destination call exit/enter
D/WifiStateMachine(  950): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  950): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  950): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  950): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  950): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  950): VerifyingLinkState enter
D/WifiStateMachine(  950): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@429019e8 on behalf of 5680
I/DownloadManager( 5680): in trimDatabase
,V/DownloadManager( 5680): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  950): send additional Connectivity Action
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  607): Reading a NULL string not supported here.
,E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  950): handleMessage: X
,D/WifiOffDelayIfNotUsed(  950): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  950): handleMessage: E msg.what=135190
D/WifiStateMachine(  950): processMsg: VerifyingLinkState
D/WifiStateMachine(  950): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  950): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  950): handleMessage: new destination call exit/enter
,W/WifiStateTracker(  950): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  950): 
W/WifiStateTracker(  950):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  950):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  950): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  950): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  950): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  950): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  950): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  950): CaptivePortalCheckState enter
D/WifiStateMachine(  950): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  950): handleMessage: X
,D/GpsLocationProvider(  950): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@42904828 on behalf of 5680
,D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  950): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  950): handleMessage: E msg.what=131092
D/WifiStateMachine(  950): processMsg: CaptivePortalCheckState
D/Nat464Xlat(  950): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  950): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  950): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  950): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  950): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/LocSvc_java(  950): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
V/DownloadManager( 5680): DownloadService onStartCommand
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
V/DownloadManager( 5680): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WifiStateMachine(  950): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/LocSvc_java(  950): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  950): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  950): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  950): transitionTo: destState=ConnectedState
I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
D/WifiStateMachine(  950): handleMessage: new destination call exit/enter
I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
D/WifiStateMachine(  950): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  950): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  950): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  950): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  950): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  950): handleMessage: X
V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@42907540 on behalf of 5680
D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  950): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
E/Parcel  (  607): Reading a NULL string not supported here.
I/LgeMiscReceiver( 4324): networkInfo.isConnected() = false
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  950): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  950): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  950): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/ActivityManager(  950): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5703 uid=10052 gids={50052, 3003}
,E/ActivityThread(  950): Failed to find provider info for com.lge.ims.provisioning
,V/DownloadManager( 5680): DownloadService onDestroy
,W/linker  ( 4609): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4609): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4609): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4609): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4609): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4609): register_HtmlEditor, Success
,D/HtmlEditor( 4609): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4609): register_HtmlEditorTimer, Success
D/HtmlEditor( 4609): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4609): register_HtmlEditorDownloader, Success
,D/HtmlEditor( 4609): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4609): register_HtmlEditorFont, Success
,D/HtmlEditor( 4609): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/QcConnectivityService(  950): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  950): handleConnectivityChange: preConnState=2 connState=1
D/HtmlEditor( 4609): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4609): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4609): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4609): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4609): register_HtmlEditorWordIterator, Success
V/        (  264): RouteController
D/HtmlEditor( 4609): JNI_OnLoad Success
I/HubEmail( 4609): JNI_OnLoad()
I/HubEmail( 4609): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4609): registerNatives()
I/HubEmail( 4609): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4609): registerNativeMethods()
I/HubEmail( 4609): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4609): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 5703): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5703): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5703): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  950): Killing 4532:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,V/        (  264): RouteController
,V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
V/LGRssiData( 5703): [loadRssi] File not exist 
V/LGRssiData( 5703): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5703): [loadFeatureFromXml] *** start feature loading from xml
V/        (  264): RouteController
W/BaseRuntimeLoader( 5703): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5703): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5703): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5703): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 5703): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5703): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5703): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  264): RouteController
V/        (  264): RouteController
D/MobileConnectivityChangeReceiver( 5703): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5703): onReceive CONNECTIVITY_CHANGE networkType=1
,V/        (  264): RouteController
I/ActivityManager(  950): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5731 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  950): Killing 4568:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,E/PhoneMonitor( 5703): onOtaspChanged old =0, new =3
,D/LocSvc_java(  950): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  607): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  607): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  607): |CAC| updateNetCfgInfo
V/QCNEA   (  607): |CAC| *********************************************
V/QCNEA   (  607): |CAC|                   Netconfig               
V/QCNEA   (  607): |CAC| *********************************************
V/QCNEA   (  607): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  607): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  607): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  607): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  607): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  607): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  607): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  607): |CAC| *********************************************
D/QCNEA   (  607): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  607): |CAC| net type = 1
V/QCNEA   (  607): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  607): |CAC| Received ssid= NG700
V/QCNEA   (  607): |CAC| 	ssid           =NG700
V/QCNEA   (  607): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  607): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  607): |CAC| *********************************************
D/QCNEA   (  607): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  607): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  607): |CAC| dispatchNetCfg: updating:0xb877e8dc
D/QCNEA   (  607): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  950): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  950): requiresClat: netType=1, hasIPv4Address=true
,V/PhoneMonitor( 5703): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/LocSvc_java(  950): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  950): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 5731): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5731): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5731): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1967): Checking schedule, now: 1453416798362 next: 1453415985126
,I/CheckinService( 1967): active receiver: enabled
,D/DhcpStateMachine(  950): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  950): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinService( 1967): Preparing to send checkin request
,I/EventLogService( 1967): Accumulating logs since 1453415952368
,I/ActivityManager(  950): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5754 uid=10066 gids={50066, 4002, 3003, 1028}
,I/CheckinRequestBuilder( 1967): Checkin reason type: 8 attempt count: 1
D/HyLog   ( 5754): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5754): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5754): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/ActivityThread( 1967): Failed to find provider info for com.google.android.wearable.settings
,D/LGDMClient( 2907): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  950): Killing 4596:com.lge.bnr/1000 (adj 15): empty #17
D/LGDMClient( 2907): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2907): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  950): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5767 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2907): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2907): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2907): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,I/LGDMClient( 2907): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 5767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5767): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5767): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  950): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5781 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  950): Killing 4205:com.android.contacts/u0a21 (adj 15): empty #17
,D/HyLog   ( 5781): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5781): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5781): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 5781): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5781): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5781): intf.getDisplayName() = lo
I/Wireless_Storage( 5781): intf.getDisplayName() = sit0
I/Wireless_Storage( 5781): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5781): intf.getDisplayName() = teql0
I/Wireless_Storage( 5781): intf.getDisplayName() = wlan0
D/NFS     ( 5781): interface name:wlan0 name:wlan0
D/NFS     ( 5781): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5781): interface name:wlan0 name:wlan0
,D/NFS     ( 5781): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 5781): CONNECT : WIFI_CONNECT
,I/ActivityManager(  950): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5793 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  950): Killing 4222:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/HyLog   ( 5793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5793): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
D/HyLog   ( 5793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1538): GC_CONCURRENT freed 1708K, 28% free 18073K/24832K, paused 2ms+2ms, total 27ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x4318f138: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1967): awaiting user notification for token
D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 5793): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  950): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5811 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5811): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5811): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5811): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5811): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5811): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5811): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5811): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5811): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5811): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5811): install
,I/MultiDex( 5811): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5811): loading existing secondary dex files
,I/MultiDex( 5811): load found 3 secondary dex files
,I/MultiDex( 5811): install done
,D/dalvikvm( 5811): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5811): VFY: unable to resolve instance field 61
,D/dalvikvm( 5811): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5811): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5811): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5811): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5811): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5811): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5811): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5811): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5811): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5811): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428cd758
D/dalvikvm( 5811): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428cd758
,D/dalvikvm( 5811): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428cd758, skipping init
,D/dalvikvm( 5811): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428cd758
,D/dalvikvm( 5811): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428cd758
,V/JNIHelp ( 5811): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5793): Binding Chromium to the main looper Looper (main, tid 1) {428c65a8}
,I/chromium( 5793): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5793): Initializing chromium process, renderers=0
,W/chromium( 5793): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5793): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5793): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5793): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5793): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5793): Remote Branch: 
I/Adreno-EGL( 5793): Local Patches: 
I/Adreno-EGL( 5793): Reconstruct Branch: 
D/dalvikvm( 5811): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428cd758
,D/dalvikvm( 5811): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428cd758
D/dalvikvm( 5811): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428cd758
,D/dalvikvm( 5811): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428cd758
,I/NSApplication( 5793): Starting up...
,I/ActivityManager(  950): Killing 4627:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/wpa_supplicant( 2023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2023): EAPOL: disable timer tick
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 5632): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5632): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 5811): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 5632): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5632): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5632): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5632): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5611): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5611): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5632): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5632): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5632): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5632): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1538): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1538): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1967): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 5811): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5811): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5811): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5811): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5811): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5811): VFY: replacing opcode 0x6e at 0x0201
,D/WearableService( 1874): callingUid 10006, callindPid: 1874
,E/MDM     ( 1426): [61] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1967): Restart initialization of location
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f72000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f72000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...,
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  950): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=2486480359
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5811): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab20f8
,D/dalvikvm( 5811): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab20f8
,D/dalvikvm( 5811): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ab20f8, skipping init
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1538): Connected
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1538): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/DhcpStateMachine(  950): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  950): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  950): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  950): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  950): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  950): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  950): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  950): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  950): RunningState
,D/WifiStateMachine(  950): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  950): handleMessage: E msg.what=131212
D/WifiStateMachine(  950): processMsg: ConnectedState
D/WifiStateMachine(  950): processMsg: L2ConnectedState
,D/WifiStateMachine(  950): processMsg: ConnectModeState
D/WifiStateMachine(  950): processMsg: DriverStartedState
D/WifiStateMachine(  950): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  950): processMsg: SupplicantStartedState
,D/WifiStateMachine(  950): processMsg: DefaultState
,D/WifiStateMachine(  950): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  950): send additional Connectivity Action
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/dalvikvm( 5811): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/LocSvc_java(  950): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/QcConnectivityService(  950): handleConnectivityChange:1 is conntected
D/WifiStateMachine(  950): handleMessage: X
,D/LocSvc_java(  950): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  950): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  950): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  950): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  950):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  950): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  950): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5878): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 5811): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5811): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 130ms
,I/Adreno-EGL( 5811): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5811): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5811): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5811): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5811): Remote Branch: 
I/Adreno-EGL( 5811): Local Patches: 
I/Adreno-EGL( 5811): Reconstruct Branch: 
,I/Adreno-EGL( 5811): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5811): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5811): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5811): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5811): Remote Branch: 
I/Adreno-EGL( 5811): Local Patches: 
I/Adreno-EGL( 5811): Reconstruct Branch: 
,I/Adreno-EGL( 5811): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5811): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5811): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5811): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5811): Remote Branch: 
I/Adreno-EGL( 5811): Local Patches: 
I/Adreno-EGL( 5811): Reconstruct Branch: 
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3486515691
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  950): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,W/Settings( 5811): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1967): Classify the device as Phone.
,V/NativeCrypto( 1967): SSL shutdown failed: ssl=0x6c784248: I/O error during system call, Connection timed out
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416800859962644; DSPS: 28869719; Offset: 1453415919826057615
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1967): GC_CONCURRENT freed 1763K, 22% free 19524K/24832K, paused 6ms+7ms, total 75ms
,I/CheckinTask( 1967): Sending checkin request (11465 bytes)
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  950): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  950): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4017): onReceive
,D/AppUp4:CustFacade( 4017): Context : android.app.ReceiverRestrictedContext@428da050
,D/AppUp4:CustFacade( 4017): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4017): isOpenOperator : true
,D/AppUp4:CustFacade( 4017): isPhone : true
,I/LicenseContentProvider( 3021): start selecting data
,D/SIMObserver( 3021): simInfo1
,I/AppUp4:EulaManager( 4017): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4017): begin check event
,I/AppUp4:CustModeStarterReceiver( 4017): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4017): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4017): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4017): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4017): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4017): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4609): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5680): DownloadService onCreate
,D/EAS     ( 4609): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4609): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  950): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  950): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/DownloadManager( 5680): in removeSpuriousFiles
,V/DownloadManager( 5680): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@4290d318 on behalf of 5680
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4324): networkInfo.isConnected() = false
W/Settings( 4609): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 5703): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5703): onReceive CONNECTIVITY_CHANGE networkType=1
I/DownloadManager( 5680): in trimDatabase
V/DownloadManager( 5680): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@4290ee58 on behalf of 5680
,D/LGDMClient( 2907): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5680): DownloadService onStartCommand
,V/DownloadManager( 5680): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@42910ec0 on behalf of 5680
,D/LGDMClient( 2907): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5767): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5680): DownloadService onDestroy
,W/ContextImpl( 5767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5781): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5781): CONNECT : WIFI_CONNECT
I/LGDMClient( 2907): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2907): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2907): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2907): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2907): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm(  950): GC_EXPLICIT freed 2080K, 49% free 30613K/59164K, paused 5ms+11ms, total 160ms
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4017): onReceive
D/AppUp4:CustFacade( 4017): Context : android.app.ReceiverRestrictedContext@428da050
D/AppUp4:CustFacade( 4017): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4017): isOpenOperator : true
,D/AppUp4:CustFacade( 4017): isPhone : true
,I/LicenseContentProvider( 3021): start selecting data
,D/SIMObserver( 3021): simInfo1
,I/AppUp4:EulaManager( 4017): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4017): begin check event
,I/AppUp4:CustModeStarterReceiver( 4017): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5680): DownloadService onCreate
,I/DownloadManager( 5680): in removeSpuriousFiles
D/EAS     ( 4609): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4609): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5680): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@42915790 on behalf of 5680
,I/DownloadManager( 5680): in trimDatabase
,V/DownloadManager( 5680): DownloadService onStartCommand
,V/DownloadManager( 5680): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5680): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@42918418 on behalf of 5680
I/LgeMiscReceiver( 4324): networkInfo.isConnected() = true
,D/PhoneState( 4324): setPdpRejectCasuse : false
,W/Settings( 4609): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 5703): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@429194e8 on behalf of 5680
,D/MobileConnectivityChangeReceiver( 5703): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5680): DownloadService onDestroy
,D/LGDMClient( 2907): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2907): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5767): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2907): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 5767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5781): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5781): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2907): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2907): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2907): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2907): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  950): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  950): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  950): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4017): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4017): onReceive
,D/AppUp4:CustFacade( 4017): Context : android.app.ReceiverRestrictedContext@428da050
,D/AppUp4:CustFacade( 4017): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4017): isOpenOperator : true
,D/AppUp4:CustFacade( 4017): isPhone : true
,I/LicenseContentProvider( 3021): start selecting data
,D/SIMObserver( 3021): simInfo1
,I/AppUp4:EulaManager( 4017): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4017): begin check event
,I/AppUp4:CustModeStarterReceiver( 4017): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4609): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5680): DownloadService onCreate
,D/EAS     ( 4609): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4324): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4324): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4324): networkInfo.isConnected() = true
,D/PhoneState( 4324): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5703): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5703): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2907): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5767): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5781): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5781): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2907): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 5680): in removeSpuriousFiles
,V/DownloadManager( 5680): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2907): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@4291cf28 on behalf of 5680
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 5680): in trimDatabase
V/DownloadManager( 5680): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/Settings( 4609): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@4291e920 on behalf of 5680
V/DownloadManager( 5680): DownloadService onStartCommand
V/DownloadManager( 5680): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5680): created cursor android.database.sqlite.SQLiteCursor@42920ad0 on behalf of 5680
E/LGDMClient( 2907): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2907): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2907): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 5680): DownloadService onDestroy
I/WifiServiceExtension(  950): MESSAGE_INTERNET_CHECK msg is received.
I/LGDMClient( 2907): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinRequestBuilder( 1967): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1967): Failed to find provider info for com.google.android.wearable.settings
,V/WifiServiceExtension(  950): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  950): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1967): awaiting user notification for token
,D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x43394ca0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1967): Classify the device as Phone.
,I/CheckinTask( 1967): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1967): Checking schedule, now: 1453416803441 next: 1453994199435
,I/CheckinService( 1967): active receiver: disabled
,I/CheckinService( 1967): Checking schedule, now: 1453416803492 next: 1453994199435
,I/CheckinService( 1967): active receiver: disabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 5793): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  950): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/ActivityManager(  950): Killing 5611:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  950): Killing 4245:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  950): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1491): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  950): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 4041): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4041): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  950): Handling package changes for user 0
,I/ActivityManager(  950): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5998 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 63ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+4ms, total 45ms
I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "sms"
,I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+4ms, total 38ms
I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "smsto"
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/ActivityManager(  950): getAssistContextExtras failed: no resumed activity
,D/HyLog   ( 5998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5998): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5998): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "mms"
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  950): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "mmsto"
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "sms"
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "smsto"
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "mms"
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  950):   Action: "android.intent.action.SENDTO"
I/PackageManager(  950):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  950):   Scheme: "mmsto"
I/PackageManager(  950): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/MediaCodecList( 5998): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5998): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5998): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5998): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 5998): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5998): MmsConfig.loadMmsSettings
,I/Babel   ( 5998): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5998): MmsConfig.loadFromDatabase
,W/Settings( 5998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseRuntimeLoader( 5998): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5998): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5998): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5998): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  950): [getValue] FEATURE key : vzw_roaming_state, value : null
E/Babel   ( 5998): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5998): MmsConfig.loadFromResources
,E/Babel   ( 5998): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5998): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/LGRssiData( 5998): [loadRssi] File not exist 
V/LGRssiData( 5998): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5998): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 4017): [getPackageName] uri : package:com.google.android.gms
,I/[LGHome]EVENT( 1491): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AppUp4  ( 4017): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4017): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/TelephonyAutoProfiling( 5998): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5998): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5998): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4017): onReceive
,V/GmsNetworkLocationProvi( 1426): DISABLE
D/AppUp4:CustFacade( 4017): Context : android.app.ReceiverRestrictedContext@428da050
D/AppUp4:CustFacade( 4017): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4017): isOpenOperator : true
,D/AppUp4:CustFacade( 4017): isPhone : true
,I/LicenseContentProvider( 3021): start selecting data
,D/SIMObserver( 3021): simInfo1
I/AppUp4:EulaManager( 4017): getAgreementForKK : Eula agreement is false
I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/AppUp4:CustModeStarterReceiver( 4017): begin check event
D/AppUp4:Utils( 4017): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4017): Event For Nothing, skip.
,I/ActivityManager(  950): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6047 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6047): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  950): applying state to connected service
,D/LocationProviderProxy(  950): applying state to connected service
,I/ActivityManager(  950): Killing 5632:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 6047): BUILD Country: EU
,I/SystemConfig( 6047): BUILD Operator: OPEN
I/SystemConfig( 6047): systemFeature RCS result false
,D/SystemConfig( 6047): refreshRcsSupport() :false
I/ActivityManager(  950): Killing 5680:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  950): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6062 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6062): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6062): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6062): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  950): Killing 4609:com.lge.email/u0a24 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2658): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  950): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6082 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 6082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6082): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6082): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6082): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 6082): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6082): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6082): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6082): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6082): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6082): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6082): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6082): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6082): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6082): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6082): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6082): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/IcingCorporaProvider( 2658): UpdateCorporaTask done [took 319 ms] updated apps [took 319 ms] 
,W/Settings( 6082): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6082): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6082): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6082): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6082): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6082): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6082): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6082): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6082): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6082): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  950): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6116 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 6082): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6082): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6082): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 6116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6116): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6116): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6082): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6082): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6082): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6082): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6082): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1967): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1967): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1967): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6116): DownloadService onCreate
,I/DownloadManager( 6116): in removeSpuriousFiles
,V/DownloadManager( 6116): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6116): DownloadService onStartCommand
,V/DownloadManager( 6116): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6116): created cursor android.database.sqlite.SQLiteCursor@42902ff8 on behalf of 6116
,V/DownloadManager( 6116): created cursor android.database.sqlite.SQLiteCursor@429056e8 on behalf of 6116
,I/DownloadManager( 6116): in trimDatabase
,V/DownloadManager( 6116): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6116): created cursor android.database.sqlite.SQLiteCursor@42908488 on behalf of 6116
,V/DownloadManager( 6116): DownloadService onDestroy
I/ActivityManager(  950): Killing 5703:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  950): GC_EXPLICIT freed 2173K, 49% free 30720K/59164K, paused 7ms+15ms, total 187ms
,V/DownloadManager( 6116): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6116): created cursor android.database.sqlite.SQLiteCursor@4290dbf8 on behalf of 6082
,D/Finsky  ( 6082): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6082): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6082): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6082): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6082): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6082): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6082): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6082): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6082): Total arena pages for JIT: 11
,I/dalvikvm( 6082): Total arena pages for JIT: 12
I/dalvikvm( 6082): Total arena pages for JIT: 13
,I/dalvikvm( 6082): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6082): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6082): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/CaptivePortalTracker(  950): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  950): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  950): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Finsky  ( 6082): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6082): [1] DailyHygiene.reschedule: Scheduling new run in 751 minutes (failures=5)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
D/CaptivePortalTracker(  950): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  950): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  950): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  950): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  950): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,I/GAV4    ( 5998): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  950): Killing 5731:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416820860961594; DSPS: 29525112; Offset: 1453415919826049485
,D/Finsky  ( 6082): [465] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6082): [1] 5.onFinished: Installation state replication succeeded.
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416840039, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416840046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416840862077888; DSPS: 30180509; Offset: 1453415919826036629
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416860863430121; DSPS: 30835913; Offset: 1453415919826046088
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416880864730113; DSPS: 31491316; Offset: 1453415919826033824
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416900058, nextTick: 59971, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416900059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416900866123491; DSPS: 32146721; Offset: 1453415919826053911
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416920868019838; DSPS: 32802143; Offset: 1453415919826058169
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416940869299257; DSPS: 33457545; Offset: 1453415919826055849
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416960039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453416960043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416960870663000; DSPS: 34112950; Offset: 1453415919826046301
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453416980872260336; DSPS: 34768362; Offset: 1453415919826056723
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 5 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 7 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 8 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 9 BSSID e8:40:f2:d6:e0:6b SSID 'WDA83' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 10 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 11 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 38:f8:89:11:e9:11]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 e8:40:f2:d6:e0:6b]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 64:7c:34:12:7f:81]
,D/WifiMonitor(  950): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 a0:c5:62:7a:49:96]
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417000873734911; DSPS: 35423771; Offset: 1453415919826035937
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417020033, nextTick: 59978, mDrawingTime: 8
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417020049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417020875202299; DSPS: 36079179; Offset: 1453415919826038481
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417040877142709; DSPS: 36734602; Offset: 1453415919826056284
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417060878447180; DSPS: 37390005; Offset: 1453415919826048499
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417080049, nextTick: 59965, mDrawingTime: 9
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417080059, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417080879803735; DSPS: 38045410; Offset: 1453415919826031763
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417100881144353; DSPS: 38700813; Offset: 1453415919826060125
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1538): GC_EXPLICIT freed 1492K, 28% free 18012K/24832K, paused 2ms+6ms, total 50ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  950): updateLightListLocked :r=NotificationRecord(0x43268050: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  950): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 6082): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6082): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6082): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6082): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6082): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6082): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6082): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6082): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 6082): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6082): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417120882533198; DSPS: 39356219; Offset: 1453415919826045161
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417140038, nextTick: 59988, mDrawingTime: 5
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417140041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417140883890118; DSPS: 40011623; Offset: 1453415919826059308
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417160885204277; DSPS: 40667026; Offset: 1453415919826061211
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417180887127395; DSPS: 41322450; Offset: 1453415919826031204
,I/ActivityManager(  950): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=6539 uid=10015 gids={50015, 3003, 1028, 1015}
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417200087, nextTick: 59941, mDrawingTime: 3
D/Clock   ( 1145): Clock updated, drawingStartTime : 1453417200090, nextTick: 59943, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/HyLog   ( 6539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6539): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6539): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Config  ( 6539): LGCalendar ver.4.2.6
,I/Config  ( 6539): start check model
I/Config  ( 6539): start check native_ca
,E/Config  ( 6539): [setCountryAndOperator] Operator=OPEN, Country=EU
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CalendarWidget( 6539): Agenda AppWidgetService got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_SCHEDULED_UPDATE dat=content://com.android.calendar typ=vnd.android.data/update flg=0x14 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory (has extras) }
,I/InitNotificationRingtoneService( 6539): Start InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager(  950): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6568 uid=10016 gids={50016, 3003, 1028, 1015}
,I/InitNotificationRingtoneService( 6539): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 6539): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 6539): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 6539): End InitializeAlertRingtoneService.onHandleIntent
D/HyLog   ( 6568): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6568): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6568): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CalendarProvider2( 6568): Created com.android.providers.calendar.CalendarAlarmManager@428e0990(com.android.providers.calendar.CalendarProvider2@428d78f8)
,I/ActivityManager(  950): Killing 5754:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/CalendarWidget( 6539): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 6539): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417200888484626; DSPS: 41977854; Offset: 1453415919826045662
,I/[LGHome]LGCalendarIcon( 1491): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 22
,I/[LGHome]LGCalendarIcon( 1491): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 22
,I/[LGHome]Launcher( 1491): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/CalendarWidget( 6539): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 6539): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,I/CalendarProvider2( 6568): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6568): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 6539): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/CalendarWidget( 6539): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 6539): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/AlertService( 6539): Beginning updateAlertNotification
,D/AlertService( 6539): No fired or scheduled alerts
,D/CalendarWidget( 6539): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 6539): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,I/ActivityManager(  950): Killing 5767:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  950): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d4f868 stackId=0, 1 tasks}
,D/ActivityManager(  950): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417220889821963; DSPS: 42633258; Offset: 1453415919826040225
,D/qcom_sensors_hal(  950): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  950): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  950): hal_ts_offset_is: Apps: 1453417240891116278; DSPS: 43288660; Offset: 1453415919826052802
,TIME-OUT KILL (timeout was 1200000ms)
```
