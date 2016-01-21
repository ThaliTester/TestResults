#### Test 56449660bb41d23_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1938): Using Auth Proxy for data requests.
W/BaseAppContext( 1938): Using Auth Proxy for data requests.
W/BaseAppContext( 1938): Using Auth Proxy for data requests.
W/GAV2    ( 4627): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  965): Killing 4114:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4364dcc8 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2}
,D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1938): GC_CONCURRENT freed 1524K, 22% free 19477K/24832K, paused 5ms+3ms, total 44ms
I/ConfigFetchService( 1938): fetch service done; releasing wakelock
I/ConfigFetchService( 1938): stopping self
I/Icing   ( 1938): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1938): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4670): 
D/AndroidRuntime( 4670): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4670): CheckJNI is OFF
I/Icing   ( 1938): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/dalvikvm( 4670): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4670): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4670): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4670): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4670): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4670): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/BatteryObserver( 1153): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/memtrack( 4670): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4670): failed to load memtrack module: -2
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
D/AndroidRuntime( 4670): Calling main entry com.android.commands.am.Am
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4670
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2050): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (118 us)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4364dcc8 stackId=1, 2 tasks}
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  965): GC_FOR_ALLOC freed 465K, 14% free 51555K/59820K, paused 146ms, total 146ms
I/dalvikvm-heap(  965): Grow heap (frag case) to 53.342MB for 856096-byte allocation
D/dalvikvm(  965): GC_FOR_ALLOC freed 23661K, 53% free 28730K/60660K, paused 111ms, total 111ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UsbSettingsControl( 2603): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2603): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4670): Shutting down VM
D/dalvikvm( 4670): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3820): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{4364dcc8 stackId=1, 2 tasks}
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4364dcc8 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3820): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3820): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4689 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4689): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4689): Binding Chromium to the background looper Looper (main, tid 1) {42c56618}
I/chromium( 4689): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/BrowserProcessMain( 4689): Initializing chromium process, renderers=0
W/chromium( 4689): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4689): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4689): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4689): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4689): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4689): Remote Branch: 
I/Adreno-EGL( 4689): Local Patches: 
I/Adreno-EGL( 4689): Reconstruct Branch: 
I/dalvikvm( 4689): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4689): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4689): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4689): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4689): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4689): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4689): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4689): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4689): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4689): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4689): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4689): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4689): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4689): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4689): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4689): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4689): Enabling debug mode 0
W/AwContents( 4689): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +461ms
W/AwContents( 4689): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  965): IME STATUS OFF
I/ActivityManager( 4689): Timeline: Activity_idle id: android.os.BinderProxy@42c57ed8 time:112772
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.467590 Y: -0.421432 Z: 9.815948 
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.452087 Y: -0.410355 Z: 9.796005 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.467590 .y:-0.421432 .z:9.815948
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.460541 Y: -0.414902 Z: 9.803146 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460541 .y:-0.414902 .z:9.803146
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1153): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/JsMessageQueue( 4689): Set native->JS mode to OnlineEventsBridgeMode
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3} time:113034
D/ActivityManager(  965): no-history finish of ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{434cdf60 ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2603): [AUTORUN] onStop()
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/dalvikvm( 4689): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c5c828
D/dalvikvm( 4689): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c5c828
D/jxcore_app_log( 4689): JniHelper::setJavaVM(0x41c0c808), pthread_self() = 1631193896
I/chromium( 4689): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4689): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4689): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4689): GC_CONCURRENT freed 2683K, 12% free 21970K/24832K, paused 3ms+3ms, total 48ms
D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 41ms
D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 37ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4689): GC_FOR_ALLOC freed 336K, 10% free 22357K/24832K, paused 25ms, total 25ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.046MB for 42652-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 103K, 11% free 22363K/24876K, paused 24ms, total 24ms
D/dalvikvm( 4689): GC_FOR_ALLOC freed 125K, 11% free 22384K/24876K, paused 25ms, total 26ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.124MB for 95956-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 179K, 11% free 22418K/24972K, paused 28ms, total 29ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.204MB for 143930-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 254K, 11% free 22466K/25116K, paused 29ms, total 29ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.318MB for 215890-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 366K, 12% free 22540K/25328K, paused 25ms, total 26ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.494MB for 323830-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 566K, 12% free 22660K/25648K, paused 25ms, total 26ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.765MB for 485740-byte allocation
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1153): usb Uevent not necessary.
D/dalvikvm( 4689): GC_FOR_ALLOC freed 861K, 13% free 22836K/26124K, paused 26ms, total 26ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4689): GC_FOR_ALLOC freed 1123K, 12% free 23077K/26124K, paused 26ms, total 26ms
D/dalvikvm( 4689): GC_FOR_ALLOC freed 207K, 12% free 23040K/26124K, paused 25ms, total 25ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 25.715MB for 1092904-byte allocation
,D/dalvikvm( 4689): GC_CONCURRENT freed 1767K, 14% free 23481K/27192K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 236K, 14% free 23400K/27192K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4689): Grow heap (frag case) to 26.588MB for 1639352-byte allocation
,D/dalvikvm( 4689): GC_CONCURRENT freed 1912K, 17% free 24010K/28796K, paused 2ms+3ms, total 40ms
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 997K, 17% free 23982K/28796K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4689): Grow heap (frag case) to 27.939MB for 2459024-byte allocation
,D/dalvikvm( 4689): GC_CONCURRENT freed 375K, 16% free 26345K/31200K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 4120K, 20% free 25017K/31200K, paused 32ms, total 33ms
,I/dalvikvm-heap( 4689): Grow heap (frag case) to 30.122MB for 3688532-byte allocation
,D/dalvikvm( 4689): GC_CONCURRENT freed 2718K, 26% free 26054K/34804K, paused 4ms+3ms, total 42ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 2022K, 25% free 26138K/34804K, paused 29ms, total 29ms
,W/jxcore-log( 4689): Initializing JXcore engine
,W/jxcore-log( 4689): JXcore engine is ready
,D/dalvikvm( 4689): GC_CONCURRENT freed 424K, 17% free 28939K/34804K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/jxcore-log( 4689): Starting JXcore engine
,W/jxcore-log( 4689): Platform android
W/jxcore-log( 4689): 
,W/jxcore-log( 4689): Process ARCH arm
W/jxcore-log( 4689): 
,I/jxcore-log( 4689): JXcore Cordova bridge is ready!
I/jxcore-log( 4689): 
,W/jxcore-log( 4689): JXcore engine is started
,E/jxcore  ( 4689): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4689): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4689): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  965): Finishing activity token=Token{44b56150 ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4364dcc8 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  965): moveHomeStack:
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  965): resumeTopActivityLocked: Resumed ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1485): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1485): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1485): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1485): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1864): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:41:44
D/UpdateThreadPoolManager( 1864): 2 : This is isUpdating : false
D/WeatherQuickCover( 1864): 2 : quick cover state : opened : 0
D/WeatherService( 1864): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1864): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1864): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1864): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1864): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1864): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:41:44
D/WeatherService( 1864): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1864): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1864): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1864): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1864): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1864): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1864): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1864): 2 : This is isUpdating : false
D/WeatherService( 1864): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1864): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1864): 2 : Map key string is -2
D/lim     ( 1864): 2 : time = 16:41
I/WeatherReflect( 1864): Model Name : LG-D802
D/WeatherTheme( 1864): 2 : Different view - status_min_formatted : 40 != 41
D/WeatherTheme( 1864): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1864): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1864): 2 : Fixed theme : optimus
,D/WeatherTheme( 1864): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1864): 2 : quick cover state : opened : 0
D/Weather.Utils( 1864): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1864): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1864): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]EVENT( 1485): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/IInputConnectionWrapper( 4689): showStatusIcon on inactive InputConnection
I/InputMethodManagerService(  965): IME STATUS OFF
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/dalvikvm( 1485): GC_CONCURRENT freed 5350K, 9% free 60842K/66376K, paused 1ms+3ms, total 25ms
,D/dalvikvm( 1485): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
D/dalvikvm( 1139): GC_CONCURRENT freed 3662K, 7% free 71668K/76408K, paused 2ms+3ms, total 35ms
D/dalvikvm( 1139): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1485): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/GAV2    ( 4627): Thread[GAThread,5,main]: No campaign data found.
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1485): GC_FOR_ALLOC freed 5022K, 9% free 62062K/68056K, paused 17ms, total 17ms
,I/ActivityManager( 1485): Timeline: Activity_idle id: android.os.BinderProxy@42c5afb0 time:116205
,D/UsbSettings( 2603): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2603): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2603): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2603): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{42c5b620 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1} time:116252
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  965): Killing 4195:com.google.android.talk/u0a77 (adj 15): empty #17
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4689): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{437b48f0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1547): onDestroy
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1485): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1485): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
E/BatteryObserver( 1153): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  289): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: X
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.460693 Y: -0.432373 Z: 9.806793 
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.447372 Y: -0.421280 Z: 9.826767 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.460693 .y:-0.432373 .z:9.806793
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.453537 Y: -0.412231 Z: 9.812897 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453537 .y:-0.412231 .z:9.812897
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4288): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4288): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453390920033, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453390920038, nextTick: 59994, mDrawingTime: 0,
,D/WeatherService( 1864): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:42:0
,D/WeatherService( 1864): 2 : TimeTick Intent And Screen On
D/WeatherService( 1864): 2 : SDK version : 19
,D/WeatherQuickCover( 1864): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1864): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1864): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1864): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1864): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1864): 2 : This is isUpdating : false
D/WeatherService( 1864): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1864): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1864): 2 : Map key string is -2
,D/lim     ( 1864): 2 : time = 16:42
,I/WeatherReflect( 1864): Model Name : LG-D802
,D/WeatherTheme( 1864): 2 : Different view - status_min_formatted : 41 != 42
D/WeatherTheme( 1864): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WeatherTheme( 1864): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1864): 2 : Fixed theme : optimus
,D/WeatherTheme( 1864): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1864): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:42:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  965): GC_CONCURRENT freed 1215K, 50% free 30474K/60660K, paused 18ms+7ms, total 193ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  965): [updateScreenState] screen on = false
,D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8382 usec
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  965): hal_acquire_resources
,I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.436569 Y: -0.407745 Z: 9.825943 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.436569 .y:-0.407745 .z:9.825943
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.445496 Y: -0.401901 Z: 9.840607 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445496 .y:-0.401901 .z:9.840607
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  363): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  965): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  965): proximitySensorChanged  positive = true
I/KnockOnPowerController(  965): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.447678 Y: -0.413254 Z: 9.813538 
,V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.449905 Y: -0.413254 Z: 9.826859 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.447678 .y:-0.413254 .z:9.813538
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.456497 Y: -0.413254 Z: 9.821640 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456497 .y:-0.413254 .z:9.821640
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.437057 Y: -0.411255 Z: 9.815094 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437057 .y:-0.411255 .z:9.815094
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.443283 Y: -0.405365 Z: 9.833176 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443283 .y:-0.405365 .z:9.833176
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@436bfc00)
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.455490 Y: -0.406189 Z: 9.828262 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455490 .y:-0.406189 .z:9.828262
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/KeyguardViewMediator( 1139): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1139): notifyScreenOnLocked
,D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb713a450
,D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1139): handleNotifyScreenOn
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/KeyguardViewManager( 1139): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
I/WindowManager(  965): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,E/SlideAside( 3820): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WifiStateMachine(  965): handleScreenStateChanged: true
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2050): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2050): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132097
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2050): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2050): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
V/SRS_Proc(  276): ParamSet string: screen_state=on
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
,V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1153): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1153): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4377a8d8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1153): enqueuing start. mLedList.size()=2
,D/qdlights( 1153): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1153): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1153): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1153): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1153): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1864): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:42:7
,I/SlideAside( 3820): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1864): 2 : This is isUpdating : false
,D/WeatherAncestor( 1864): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:42:7
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1864): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1864): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1864): 2 : TimeTick Receiver Unregister
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1864): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1153): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1153): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1153): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1153): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1153): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1153): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1153): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1153): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 421ms
D/qdlights( 1153): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1153): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1153): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1153): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1153): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 177, B = 177
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
D/qdlights( 1153): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 171, B = 171
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Clock   ( 1139): Clock updated, drawingStartTime : 1453390927693, nextTick: 52339, mDrawingTime: 1
,D/qdlights( 1153): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453390927711, nextTick: 52321, mDrawingTime: 0
,D/qdlights( 1153): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 159, B = 159
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/qdlights( 1153): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 153, B = 153
D/WeatherService( 1864): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:42:7
,D/WeatherService( 1864): 2 : ACTION screen on
,D/WeatherService( 1864): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1864): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:42:7
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1153): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 147, B = 147
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,D/qdlights( 1153): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 141, B = 141
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1139): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1139): notifyScreenOffLocked
,D/qdlights( 1153): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 135, B = 135
,I/[LGHome]EVENT( 1485): [Launcher.java:894:onPause()]onPause
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1153): usb Uevent not necessary.
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1}
,D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
D/qdlights( 1153): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 129, B = 129
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1153): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 123, B = 123
,D/KeyguardViewMediator( 1139): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  965): Vibrator off
,I/[LGHome]EVENT( 1485): [Launcher.java:4955:onStop()]onStop
D/KeyguardViewMediator( 1139): handleNotifyScreenOff
,D/KeyguardViewManager( 1139): onScreenTurnedOff()
D/qdlights( 1153): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 117, B = 117
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  965): handleScreenStateChanged: false
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1153): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 111, B = 111
D/WifiController(  965): CMD_SCREEN_OFF 
D/WifiController(  965): shouldWifiStayAwake TRUE
,V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{43506030 u0 com.lge.launcher2/.Launcher t1} (stop complete)
E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
,E/CliptrayService( 1153): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1153): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1153): clear
D/qdlights( 1153): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 105, B = 105
D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
D/WifiStateMachine(  965): handleMessage: X
,I/[LGHome]EVENT( 1485): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1153): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 99, B = 99
D/WeatherService( 1864): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:42:7
,D/WeatherService( 1864): 2 : ACTION screen off
,D/WeatherService( 1864): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:42:7
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/qdlights( 1153): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 93, B = 93
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
D/qdlights( 1153): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1153): [Current] = 255, R = 0, G = 87, B = 87
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
,D/NfcService( 1472): NFC-C OFF
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1459): [TangibleIO] LCD is off. Remove tangible if exist.
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1153): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1153): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1153): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1153): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1153): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1153): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1153): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1153): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1153): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1153): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1153): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1153): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1153): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1153): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1153): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1153): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1153): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,I/Sensors (  363): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,E/ThermalEngine(  289): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1139): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1139): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1139): OMADM Lock is OFF
,D/KeyguardViewMediator( 1139): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1139): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453390935940893496; DSPS: 4950986; Offset: 1453390784848791446
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453390955942190832; DSPS: 5606389; Offset: 1453390784848776526
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2050): nl80211: Disconnect event
D/wpa_supplicant( 2050): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2050): wlan0: Deauthentication notification
D/wpa_supplicant( 2050): wlan0:  * reason 0
D/wpa_supplicant( 2050): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2050): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2050): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2050): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2050): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2050): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2050): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
,D/WifiStateMachine(  965): handleMessage: E msg.what=147460,
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState,
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb878bd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2050): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state INITIALIZE,
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2050): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection lost
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
,D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/wpa_supplicant( 2050): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2050): wlan0: nl80211: scan request
,D/wpa_supplicant( 2050): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2050): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2050): wlan0: nl80211: Scan trigger
,D/WifiNative-wlan0(  965):    returned true
,D/DhcpStateMachine(  965): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  965): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1153): handleWifiStateChangedEvent: 0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
D/QCNEA   (  400): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  400): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  400): |CAC| updateNetCfgInfo
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC|                   Netconfig               
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  400): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  400): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  400): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  400): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  400): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  400): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| Received bssid= 
D/QCNEA   (  400): |CAC| net type = 3
V/QCNEA   (  400): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  400): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  400): |CAC| 	ssid           =NG700
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  400): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  400): |CAC| dispatchNetCfg: updating:0xb87f38dc
,D/QCNEA   (  400): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiHS20(  965): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
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
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  270): RouteController
V/        (  270): RouteController
,V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4929 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  270): RouteController
,D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4929): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,W/NetworkManagementService(  965): route cmd failed: 
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
,D/NetUtils(  965): android_net_utils_resetConnections in env=0x628242c0 clazz=0x6ae00001 iface=wlan0 mask=0x3
,I/PCSuite ( 4929): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/NativeCrypto( 1547): Read error: ssl=0x63931d18: I/O error during system call, Connection timed out
,D/QcConnectivityService(  965): resetConnections(wlan0, 3)
V/NativeCrypto( 1547): SSL shutdown failed: ssl=0x63931d18: I/O error during system call, Broken pipe
D/PCSuite ( 4929): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4929): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4970 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  965): Killing 3150:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/dalvikvm( 1547): GC_EXPLICIT freed 1209K, 29% free 17826K/24832K, paused 3ms+8ms, total 70ms
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/DhcpStateMachine(  965): StoppedState
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/HyLog   ( 4970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4970): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4970): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 4970): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4970): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4970): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4970): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4970): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4970): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4970): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4970): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 3977:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2050): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2050): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2050): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2050): nl80211: Survey data missing
D/wpa_supplicant( 2050): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 6 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 9 BSSID 0c:bd:51:2b:c1:25 SSID 'PLAY-ONLINE_1167'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2050): wlan0: New scan results available
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2050): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2050): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2050): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2050): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2050): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2050): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2050): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2050): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 2050): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2050): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2050): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2050): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2050): WPS: AP[4] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2050): WPS: AP[5] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2050): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2050): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2050): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2050): wlan0: 2: 64:7c:34:12:7f:81 s,sid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-62 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 3: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-71 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 6: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-90 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 7: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-86 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2050): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
,D/wpa_supplicant( 2050): wlan0: Selecting BSS from priority group 1,
D/wpa_supplicant( 2050): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 2050): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2050): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2050): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
,D/wpa_supplicant( 2050): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb878d5a8  current_ssid=0x0,
D/wpa_supplicant( 2050): scard is not null..
D/wpa_supplicant( 2050): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0,
,D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00,
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2050): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2050): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2050): wlan0: Cancelling scan request
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): wlan0: WPA: clearing own WPA/RSN IE,
D/wpa_supplicant( 2050): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2050): RSN: PMKSA cache search - network_ctx=0xb878d5a8 try_opportunistic=0
D/wpa_supplicant( 2050): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2050): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2050): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2050): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2050): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2050): wlan0: WPA: using PTK CCMP
,D/wpa_supplicant( 2050): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2050): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0,
D/wpa_supplicant( 2050): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2050): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2050): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2050): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2050): nl80211: Unsubscribe mgmt frames handle 0xb878c590 (mode change),
D/wpa_supplicant( 2050): nl80211: Subscribe to mgmt frames with non-AP handle 0xb878c590
,D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
,D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09,
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2050): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2050):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2050):   * freq=2412
D/wpa_supplicant( 2050):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2050):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050):   * Auth Type 0
D/wpa_supplicant( 2050):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 64:7c:34:12:7f:81]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 dc:4a:3e:0f:c2:f1]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 06:7c:34:12:7f:81]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:97]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 0c:bd:51:2b:c1:25]
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE ,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
,D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/wpa_supplicant( 2050): nl80211: Connect request send successfully
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2050): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2050): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2050): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2050): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2050): nl80211: Connect event
D/wpa_supplicant( 2050): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2050): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2050): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2050): wlan0: Association info event
D/wpa_supplicant( 2050): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2050): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2050): wlan0: freq=2412 MHz
D/wpa_supplicant( 2050): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2050): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2050): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2050): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): scard is not null..
D/wpa_supplicant( 2050): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2050): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2050): TDLS: Remove peers on association
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2050): EAPOL: enable timer tick
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): wlan0: Cancelling scan request
,D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 2050): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c7 eb 61 43 6e e7 ba 9b 80 02 9f d6 58 99 8a ...
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2050): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2050): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2050): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2050):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2050):   key_nonce - hexdump(len=32): c7 eb 61 43 6e e7 ba 9b 80 02 9f d6 58 99 8a b3 04 46 e8 7e fc 3b 35 f8 dd db 17 eb 5d 3b 3a 84
D/wpa_supplicant( 2050):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c7 eb 61 43 6e e7 ba 9b 80 02 9f d6 58 99 8a ...
D/wpa_supplicant( 2050): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2050): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2050): Get randomness: len=32 entropy=9
D/wpa_supplicant( 2050): WPA: Renewed SNonce - hexdump(len=32): 0a 22 c6 ee 23 e1 13 be 91 97 d9 43 19 f5 24 26 6a ff 0b 08 87 16 f1 52 96 cf c6 79 b9 78 b1 31
,D/wpa_supplicant( 2050): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): WPA: Nonce1 - hexdump(len=32): 0a 22 c6 ee 23 e1 13 be 91 97 d9 43 19 f5 24 26 6a ff 0b 08 87 16 f1 52 96 cf c6 79 b9 78 b1 31
D/wpa_supplicant( 2050): WPA: Nonce2 - hexdump(len=32): c7 eb 61 43 6e e7 ba 9b 80 02 9f d6 58 99 8a b3 04 46 e8 7e fc 3b 35 f8 dd db 17 eb 5d 3b 3a 84
D/wpa_supplicant( 2050): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2050): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2050): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2050): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2050): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): WPA: Derived Key MIC - hexdump(len=16): 32 1e 29 9a 44 c9 0a 67 ae ae 2e a5 54 17 05 b9
,D/wpa_supplicant( 2050): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 0a 22 c6 ee 23 e1 13 be 91 97 d9 43 19 f5 24 ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 2050): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c7 eb 61 43 6e e7 ba 9b 80 02 9f d6 58 99 8a ...
D/wpa_supplicant( 2050): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2050): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2050): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2050): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2050):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2050):   key_nonce - hexdump(len=32): c7 eb 61 43 6e e7 ba 9b 80 02 9f d6 58 99 8a b3 04 46 e8 7e fc 3b 35 f8 dd db 17 eb 5d 3b 3a 84
D/wpa_supplicant( 2050):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_rsc - hexdump(len=8): 17 28 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_mic - hexdump(len=16): 39 f0 8a 76 90 1f 65 d8 3a c7 7d 8f b5 02 2c 8f
D/wpa_supplicant( 2050): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c7 eb 61 43 6e e7 ba 9b 80 02 9f d6 58 99 8a ...
D/wpa_supplicant( 2050): RSN: encrypted key data - hexdump(len=56): 64 91 a3 20 f8 78 3f 31 ce 90 45 59 45 78 33 7d 21 62 63 33 11 be b1 b7 d2 17 5c 23 de 4b 55 36 ...
D/wpa_supplicant( 2050): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2050): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2050): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2050): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 73 0b ...
D/wpa_supplicant( 2050): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2050): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2050): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): WPA: Derived Key MIC - hexdump(len=16): 7d 04 ca bf 13 97 97 25 4b 2b f3 c2 99 64 c8 d8
D/wpa_supplicant( 2050): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2050): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb878cc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2050):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2050): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2050): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2050): WPA: RSC - hexdump(len=6): 17 28 00 00 00 00
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ef403a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2050):    broadcast key
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
I/wpa_supplicant( 2050): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2050): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2050): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2050): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2050): EAPOL authentication completed successfully
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147459
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection established
,D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2050): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-36ms what=147462 obj=android.net.wifi.StateChangeResult@43fb28f0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/DhcpStateMachine(  965): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-28ms what=147462 obj=android.net.wifi.StateChangeResult@43fb6ca0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-28ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1,
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :false
I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
D/AppUp4:CustFacade( 4077): isPhone : true
I/LicenseContentProvider( 2987): start selecting data
D/SIMObserver( 2987): simInfo1
I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity
,I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5020 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5020): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
,D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring up wlan0
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  965): handleMessage: X
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4369ad30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4369ad30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
,D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
E/Parcel  (  400): Reading a NULL string not supported here.
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): CaptivePortalCheckState enter
,D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  965): handleMessage: X
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
V/WfdStateTracker( 1153): handleWifiStateChangedEvent: 1
E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
,V/        (  270): RouteController
,V/DownloadManager( 5020): DownloadService onCreate
,I/DownloadManager( 5020): in removeSpuriousFiles
,D/EAS     ( 4608): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5020): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42c9cdb8 on behalf of 5020
D/EAS     ( 4608): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
V/        (  270): RouteController
,I/DownloadManager( 5020): in trimDatabase
V/DownloadManager( 5020): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42c9ec08 on behalf of 5020
,V/DownloadManager( 5020): DownloadService onStartCommand
,V/DownloadManager( 5020): DownloadService onStartCommand
D/eas_req ( 4608): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 5020): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42ca1920 on behalf of 5020
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/DownloadManager( 5020): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42ca5978 on behalf of 5020
I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = false
,V/        (  270): RouteController
,W/linker  ( 4608): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4608): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4608): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4608): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4608): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4608): register_HtmlEditor, Success
D/HtmlEditor( 4608): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
,D/HtmlEditor( 4608): register_HtmlEditorTimer, Success
D/HtmlEditor( 4608): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4608): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4608): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4608): register_HtmlEditorFont, Success
D/HtmlEditor( 4608): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4608): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4608): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4608): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4608): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4608): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4608): JNI_OnLoad Success
,I/HubEmail( 4608): JNI_OnLoad()
I/HubEmail( 4608): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4608): registerNatives()
I/HubEmail( 4608): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4608): registerNativeMethods()
,I/HubEmail( 4608): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4608): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/        (  270): RouteController
,V/DownloadManager( 5020): DownloadService onDestroy
,V/        (  270): RouteController
,V/        (  270): RouteController
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5053 uid=10052 gids={50052, 3003}
,V/        (  270): RouteController
I/ActivityManager(  965): Killing 4351:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/HyLog   ( 5053): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5053): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5053): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/QCNEA   (  400): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  400): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  400): |CAC| updateNetCfgInfo
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC|                   Netconfig               
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  400): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  400): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  400): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  400): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  400): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  400): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| net type = 1
V/QCNEA   (  400): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| Received ssid= NG700
V/QCNEA   (  400): |CAC| 	ssid           =NG700
V/QCNEA   (  400): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  400): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  400): |CAC| dispatchNetCfg: updating:0xb87f38dc
D/QCNEA   (  400): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5053): [loadRssi] File not exist 
,V/LGRssiData( 5053): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5053): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 5053): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5053): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5053): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5053): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 5053): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5053): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5053): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 5053): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5053): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5074 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4534:com.android.defcontainer/u0a4 (adj 15): empty #17
,E/PhoneMonitor( 5053): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5053): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5074): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5074): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5074): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1938): Checking schedule, now: 1453390961136 next: 1453390850701
,I/CheckinService( 1938): active receiver: enabled
,I/CheckinService( 1938): Preparing to send checkin request
,I/EventLogService( 1938): Accumulating logs since 1453390817920
,I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5095 uid=10066 gids={50066, 4002, 3003, 1028}
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  965): Killing 4568:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5095): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5095): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5095): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  965): Killing 4596:com.lge.bnr/1000 (adj 15): empty #17
D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5108 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5108): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5108): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5108): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5108): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5122 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  965): Killing 4251:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5122): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5122): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Wireless_Storage( 5122): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5122): intf.getDisplayName() = lo
I/Wireless_Storage( 5122): intf.getDisplayName() = sit0
I/Wireless_Storage( 5122): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5122): intf.getDisplayName() = teql0
I/Wireless_Storage( 5122): intf.getDisplayName() = wlan0
D/NFS     ( 5122): interface name:wlan0 name:wlan0
D/NFS     ( 5122): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5122): interface name:wlan0 name:wlan0
V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/NFS     ( 5122): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 5122): CONNECT : WIFI_CONNECT
E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5135 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4265:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/dalvikvm(  274): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 29ms
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 23ms
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
D/HyLog   ( 5135): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5135): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5135): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 24ms
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x435039e8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GAV2    ( 5135): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5150 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5150): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5150): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5150): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5150): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5150): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5150): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5150): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5150): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5150): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5150): install
,I/MultiDex( 5150): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5150): loading existing secondary dex files
,I/MultiDex( 5150): load found 3 secondary dex files
,I/MultiDex( 5150): install done
,D/dalvikvm( 5150): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5150): VFY: unable to resolve instance field 61
,D/dalvikvm( 5150): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5150): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5150): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5150): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5150): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5150): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5150): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5150): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5150): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5150): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c51430
,D/dalvikvm( 5150): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c51430
,D/dalvikvm( 5150): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c51430, skipping init
D/dalvikvm( 5150): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c51430
,D/dalvikvm( 5150): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c51430
,V/JNIHelp ( 5150): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 5150): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c51430
,D/dalvikvm( 5150): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42c51430
D/dalvikvm( 5150): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c51430
,D/dalvikvm( 5150): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42c51430
,V/WebViewChromium( 5135): Binding Chromium to the main looper Looper (main, tid 1) {42c605a0}
,I/chromium( 5135): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5135): Initializing chromium process, renderers=0
,W/chromium( 5135): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5135): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5135): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5135): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5135): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5135): Remote Branch: 
I/Adreno-EGL( 5135): Local Patches: 
I/Adreno-EGL( 5135): Reconstruct Branch: 
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2050): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2050): EAPOL: disable timer tick
,I/ProviderInstaller( 5150): Installed default security provider GmsCore_OpenSSL
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm( 5150): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5150): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5150): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5150): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5150): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5150): VFY: replacing opcode 0x6e at 0x0201
,D/dalvikvm(  965): GC_EXPLICIT freed 2193K, 49% free 30567K/59276K, paused 4ms+12ms, total 156ms
,I/NSApplication( 5135): Starting up...
,I/ActivityManager(  965): Killing 4627:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2a000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2a000
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4970): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,I/QRemote ( 4970): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4970): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4929): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4929): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/QRemote ( 4970): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4970): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4970): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4970): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=883798355
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1547): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1547): Proximity feature is not enabled.
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WearableService( 1834): callingUid 10006, callindPid: 1834
,E/MDM     ( 1422): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/LocationInitializer( 1938): Restart initialization of location
,D/dalvikvm( 5150): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e90e60
D/dalvikvm( 5150): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e90e60
,D/dalvikvm( 5150): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e90e60, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/ProcessCpuTracker(  965): Skipping unknown process pid 5203
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/DhcpStateMachine(  965): DHCP succeeded on wlan0
D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  965): RunningState
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
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
,D/WVCdm   (  276): PrepareKeyRequest: nonce=981285579
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1,
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0,
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5150): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5222): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5150): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5150): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 102ms
,I/Adreno-EGL( 5150): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5150): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5150): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5150): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5150): Remote Branch: 
I/Adreno-EGL( 5150): Local Patches: 
I/Adreno-EGL( 5150): Reconstruct Branch: 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5150): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5150): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5150): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5150): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5150): Remote Branch: 
I/Adreno-EGL( 5150): Local Patches: 
I/Adreno-EGL( 5150): Reconstruct Branch: 
,I/Adreno-EGL( 5150): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5150): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5150): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5150): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5150): Remote Branch: 
I/Adreno-EGL( 5150): Local Patches: 
I/Adreno-EGL( 5150): Reconstruct Branch: 
,W/Settings( 5150): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1938): Sending checkin request (11465 bytes)
,D/GCM     ( 1547): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1547): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,D/dalvikvm( 1153): GC_CONCURRENT freed 2907K, 11% free 25444K/28528K, paused 3ms+2ms, total 32ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
D/AppUp4:CustFacade( 4077): isPhone : true
I/LicenseContentProvider( 2987): start selecting data
D/SIMObserver( 2987): simInfo1
I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4077): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4077): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4077): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4077): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4077): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 5020): DownloadService onCreate
,I/DownloadManager( 5020): in removeSpuriousFiles
,D/EAS     ( 4608): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4608): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4608): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 5020): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42caa0d8 on behalf of 5020
,V/DownloadManager( 5020): DownloadService onStartCommand
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,I/DownloadManager( 5020): in trimDatabase
V/DownloadManager( 5020): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5020): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4375): networkInfo.isConnected() = false
V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cac2c0 on behalf of 5020
D/MobileConnectivityChangeReceiver( 5053): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cad358 on behalf of 5020
D/MobileConnectivityChangeReceiver( 5053): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4608): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/LGDMSGCM( 5108): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5020): DownloadService onDestroy
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 5108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5122): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5122): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/VacuumService( 1547): Vacuum at: now=1453390964299 tag=VacuumService
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GoogleURLConnFactory( 1547): Using platform SSLCertificateSocketFactory
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1547): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/LicenseContentProvider( 2987): start selecting data
,W/Uploader( 1547): No account for auth token provided
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5020): DownloadService onCreate
,I/DownloadManager( 5020): in removeSpuriousFiles
,V/DownloadManager( 5020): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cb1e88 on behalf of 5020
,D/EAS     ( 4608): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4608): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 5020): in trimDatabase
,V/DownloadManager( 5020): DownloadService onStartCommand
,V/DownloadManager( 5020): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cb38e8 on behalf of 5020
,V/DownloadManager( 5020): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cb5530 on behalf of 5020
,W/Settings( 4608): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5020): DownloadService onDestroy
I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = true
,D/PhoneState( 4375): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5053): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5053): onReceive CONNECTIVITY_CHANGE networkType=1
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5108): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 5108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5122): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5122): CONNECT : WIFI_CONNECT
I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Uploader( 1547):  no longer exists, so no auth token.
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x44fc97f8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,I/CheckinTask( 1938): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/Uploader( 1547): No account for auth token provided
,I/CheckinService( 1938): Checking schedule, now: 1453390964745 next: 1453968360737
,I/CheckinService( 1938): active receiver: disabled
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
I/CheckinService( 1938): Checking schedule, now: 1453390964815 next: 1453968360737
,I/CheckinService( 1938): active receiver: disabled
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
,D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4608): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5020): DownloadService onCreate
,D/EAS     ( 4608): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = true
,D/PhoneState( 4375): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5053): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5053): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5108): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5122): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5122): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 5020): in removeSpuriousFiles
,V/DownloadManager( 5020): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cb96b8 on behalf of 5020
I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5020): DownloadService onStartCommand
,W/Settings( 4608): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5020): in trimDatabase
,V/DownloadManager( 5020): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5020): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cbb618 on behalf of 5020
,V/DownloadManager( 5020): created cursor android.database.sqlite.SQLiteCursor@42cbcdb8 on behalf of 5020
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 5020): DownloadService onDestroy
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 5135): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  965): Killing 4288:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1485): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5334 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/administrator(  965): Handling package changes for user 0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3820): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3820): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
,D/HyLog   ( 5334): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5334): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5334): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
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
,I/Babel   ( 5334): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5334): MmsConfig.loadMmsSettings
I/Babel   ( 5334): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5334): MmsConfig.loadFromDatabase
I/MediaCodecList( 5334): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5334): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5334): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5334): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5334): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5334): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5334): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5334): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 5334): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5334): MmsConfig.loadFromResources
,E/Babel   ( 5334): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5334): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5334): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4077): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 4077): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 4077): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/LGRssiData( 5334): [loadRssi] File not exist 
,V/LGRssiData( 5334): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5334): [loadFeatureFromXml] *** start feature loading from xml
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/TelephonyAutoProfiling( 5334): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5334): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5334): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
,D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,D/AppUp4:Utils( 4077): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4077): Event For Nothing, skip.
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5384 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/HyLog   ( 5384): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5384): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5384): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
,I/SystemConfig( 5384): BUILD Country: EU
,I/SystemConfig( 5384): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 4929:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5399 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,I/SystemConfig( 5384): systemFeature RCS result false
,D/SystemConfig( 5384): refreshRcsSupport() :false
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5399): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5399): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5399): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  965): GC_EXPLICIT freed 2674K, 49% free 30655K/59276K, paused 5ms+13ms, total 173ms
,I/ActivityManager(  965): Killing 4970:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): Killing 5020:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2672): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5417 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5417): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5417): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5417): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5417): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5417): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5417): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5417): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 1938): GC_CONCURRENT freed 1880K, 22% free 19579K/24832K, paused 4ms+4ms, total 45ms
,I/dalvikvm( 5417): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5417): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5417): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5417): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5417): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5417): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5417): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5417): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5417): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5417): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5417): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5417): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5417): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5417): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5417): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5417): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5417): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5417): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5417): VFY: replacing opcode 0x6e at 0x029a
,I/IcingCorporaProvider( 2672): UpdateCorporaTask done [took 297 ms] updated apps [took 297 ms] 
,I/dalvikvm( 5417): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 5417): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5417): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  965): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5451 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5451): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5451): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5451): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5417): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5417): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5417): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5417): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5417): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  965): Killing 4608:com.lge.email/u0a24 (adj 15): empty #17
,D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1938): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,I/Icing   ( 1938): updateResources: need to parse f{com.google.android.gms}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm( 1547): GC_CONCURRENT freed 1707K, 28% free 18039K/24832K, paused 3ms+3ms, total 34ms
,V/DownloadManager( 5451): DownloadService onCreate
,I/DownloadManager( 5451): in removeSpuriousFiles
,V/DownloadManager( 5451): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5451): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42c9f1e0 on behalf of 5417
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42c9fce8 on behalf of 5451
,I/DownloadManager( 5451): in trimDatabase
,V/DownloadManager( 5451): DownloadService onStartCommand
,V/DownloadManager( 5451): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5451): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 5417): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42ca5270 on behalf of 5451
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42ca3520 on behalf of 5451
,D/Finsky  ( 5417): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/DownloadManager( 5451): DownloadService onDestroy
I/ActivityManager(  965): Killing 5053:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  965): battery changed pluggedType: 2
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5417): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5417): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5417): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5417): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5417): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5417): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 5417): Total arena pages for JIT: 11
,I/dalvikvm( 5417): Total arena pages for JIT: 12
I/dalvikvm( 5417): Total arena pages for JIT: 13
,I/dalvikvm( 5417): Total arena pages for JIT: 14
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1216): Disconnected process message: 10
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5417): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5417): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/Finsky  ( 5417): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5417): [1] DailyHygiene.reschedule: Scheduling new run in 93 minutes (failures=3)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453390975943649678; DSPS: 6261797; Offset: 1453390784848770528
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1153): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/GAV4    ( 5334): Thread[GAThread,5,main]: No campaign data found.
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453390980055, nextTick: 59976, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453390980056, nextTick: 59977, mDrawingTime: 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5417): [471] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5417): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453390995944570347; DSPS: 6917187; Offset: 1453390784848775670
,D/wpa_supplicant( 2050): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 4 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:26:f2:18:08:c8]
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391015945449247; DSPS: 7572576; Offset: 1453390784848769560
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391035946757260; DSPS: 8227978; Offset: 1453390784848795835
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391040049, nextTick: 59981, mDrawingTime: 1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391040052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391055948097565; DSPS: 8883382; Offset: 1453390784848793366
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391075949391827; DSPS: 9538785; Offset: 1453390784848775372
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391095950672810; DSPS: 10194187; Offset: 1453390784848774617
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391100052, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391100055, nextTick: 59977, mDrawingTime: 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 2657): GC_CONCURRENT freed 7891K, 33% free 16761K/24832K, paused 2ms+1ms, total 33ms
,D/dalvikvm( 2657): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391115952059000; DSPS: 10849592; Offset: 1453390784848787516
,I/LocationManagerService(  965): remove 434e8d28
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2657): GC_CONCURRENT freed 1753K, 32% free 17055K/24832K, paused 3ms+1ms, total 29ms
,D/dalvikvm( 2657): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2657): GC_CONCURRENT freed 1839K, 31% free 17263K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2657): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Mlt MonitorService( 2657): parseLastkmsg to dump
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391135953995555; DSPS: 11505015; Offset: 1453390784848801464
,D/wpa_supplicant( 2050): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 6 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 9 BSSID 0c:bd:51:2b:c1:25 SSID 'PLAY-ONLINE_1167' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:97]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 0c:bd:51:2b:c1:25]
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391155955322266; DSPS: 12160419; Offset: 1453390784848785401
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391160046, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391160055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391175956682258; DSPS: 12815824; Offset: 1453390784848772102
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391195957972302; DSPS: 13471226; Offset: 1453390784848780408
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1139): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1216): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1139): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1459): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1459): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1459): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1459): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391215959303648; DSPS: 14126630; Offset: 1453390784848768981
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391220045, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391220051, nextTick: 59981, mDrawingTime: 0
,D/dalvikvm( 2657): GC_CONCURRENT freed 1956K, 31% free 17233K/24832K, paused 11ms+3ms, total 72ms
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391235960696090; DSPS: 14782035; Offset: 1453390784848788132
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391255961976499; DSPS: 15437437; Offset: 1453390784848786802
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  965): GC_EXPLICIT freed 1251K, 49% free 30619K/59276K, paused 4ms+11ms, total 168ms
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/GLSActivity( 1547): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1547): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1547): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5417): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5417): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5417): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4362dc20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/System  ( 5417): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5417): isDataSchedulerEnabled():false
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391275964370398; DSPS: 16092876; Offset: 1453390784848769813
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391280057, nextTick: 59974, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391280058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391295965715389; DSPS: 16748280; Offset: 1453390784848772030
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391315966150017; DSPS: 17403654; Offset: 1453390784848779412
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391335967456885; DSPS: 18059057; Offset: 1453390784848774024
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391340040, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391340057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391355968873856; DSPS: 18714463; Offset: 1453390784848787187
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391375969980203; DSPS: 19369860; Offset: 1453390784848764383
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391395971237644; DSPS: 20025261; Offset: 1453390784848770603
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391400041, nextTick: 59988, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391400061, nextTick: 59971, mDrawingTime: 0
,I/ActivityManager(  965): Killing 5074:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391415972221959; DSPS: 20680653; Offset: 1453390784848778356
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391435974105701; DSPS: 21336075; Offset: 1453390784848770008
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391455975392620; DSPS: 21991477; Offset: 1453390784848775189
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391460041, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391460055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391475976317821; DSPS: 22646867; Offset: 1453390784848784863
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391495977212554; DSPS: 23302256; Offset: 1453390784848794586
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391515978067389; DSPS: 23957644; Offset: 1453390784848794929
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391520026, nextTick: 59996, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391520058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391535978993944; DSPS: 24613035; Offset: 1453390784848775439
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391555979888884; DSPS: 25268424; Offset: 1453390784848785369
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391575981164762; DSPS: 25923826; Offset: 1453390784848779509
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391580064, nextTick: 59959, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391580070, nextTick: 59963, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391595982076056; DSPS: 26579216; Offset: 1453390784848775275
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391615982534642; DSPS: 27234591; Offset: 1453390784848776098
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391635984395469; DSPS: 27890012; Offset: 1453390784848775352
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391640028, nextTick: 60001, mDrawingTime: 3
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391640049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391655985751398; DSPS: 28545416; Offset: 1453390784848788508
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2050): nl80211: Disconnect event
D/wpa_supplicant( 2050): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2050): wlan0: Deauthentication notification
D/wpa_supplicant( 2050): wlan0:  * reason 0
D/wpa_supplicant( 2050): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2050): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2050): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2050): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2050): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2050): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2050): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147460
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection lost
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb878bd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
,D/DhcpStateMachine(  965): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine(  965): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1153): handleWifiStateChangedEvent: 0
,D/WifiHS20(  965): hidePasspointNotification off =false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/QCNEA   (  400): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  400): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  400): |CAC| updateNetCfgInfo
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC|                   Netconfig               
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  400): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  400): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  400): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  400): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  400): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  400): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| Received bssid= 
D/QCNEA   (  400): |CAC| net type = 3
V/QCNEA   (  400): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  400): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  400): |CAC| 	ssid           =NG700
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  400): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  400): |CAC| dispatchNetCfg: updating:0xb87f38dc
D/QCNEA   (  400): |CAC| readCallback: read len:0, ret:-1, errno:11
D/wpa_supplicant( 2050): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2050): wlan0: nl80211: scan request
D/wpa_supplicant( 2050): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2050): Scan requested (ret=0) - scan timeout 30 seconds
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2050): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  965): handleMessage: X
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  270): RouteController
,V/        (  270): RouteController
,I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6185 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  270): RouteController
,V/        (  270): RouteController
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  270): RouteController
V/        (  270): RouteController
V/        (  270): RouteController
D/HyLog   ( 6185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6185): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6185): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  270): RouteController
W/NetworkManagementService(  965): route cmd failed: 
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
,D/NetUtils(  965): android_net_utils_resetConnections in env=0x628242c0 clazz=0xb7500001 iface=wlan0 mask=0x3
D/QcConnectivityService(  965): resetConnections(wlan0, 3)
,V/NativeCrypto( 1547): Read error: ssl=0x63933320: I/O error during system call, Connection timed out
,V/NativeCrypto( 1547): SSL shutdown failed: ssl=0x63933320: I/O error during system call, Broken pipe
,I/PCSuite ( 6185): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6185): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6185): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6227 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  965): StoppedState
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  965): Killing 5095:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/HyLog   ( 6227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6227): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 6227): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/QRemote ( 6227): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 6227): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6227): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6227): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6227): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6227): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6227): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6227): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 5108:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2050): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2050): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2050): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2050): nl80211: Survey data missing
D/wpa_supplicant( 2050): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 10 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 11 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2050): wlan0: New scan results available
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2050): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2050): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2050): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2050): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2050): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2050): wlan0: 2: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2050): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2050): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2050): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2050): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2050): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb878d5a8  current_ssid=0x0
D/wpa_supplicant( 2050): scard is not null..
D/wpa_supplicant( 2050): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg_m,dm_auto_connect_policy 0
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2050): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2050): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2050): wlan0: Cancelling scan request
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2050): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2050): RSN: PMKSA cache search - network_ctx=0xb878d5a8 try_opportunistic=0
D/wpa_supplicant( 2050): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RSN: No PMKSA cache entry found,
,D/wpa_supplicant( 2050): wlan0: RSN: using IEEE 802.11i/D9.0,
D/wpa_supplicant( 2050): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2050): wlan0: WPA: clearing AP WPA IE
,D/wpa_supplicant( 2050): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2050): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2050): wlan0: WPA: using KEY_MGMT WPA-PSK
,D/wpa_supplicant( 2050): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2050): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2050): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2050): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2050): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2050): nl80211: Unsubscribe mgmt frames handle 0xb878c590 (mode change),
D/wpa_supplicant( 2050): nl80211: Subscribe to mgmt frames with non-AP handle 0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0c,
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590,
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590,
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2050): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2050):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050):   * freq=2412
D/wpa_supplicant( 2050):   * SSID - hexdump(len=5): 4e 47 37 30 30,
,D/wpa_supplicant( 2050):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050):   * Auth Type 0
D/wpa_supplicant( 2050):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 2050): nl80211: Connect request send successfully
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
,D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 06:7c:34:12:7f:81]
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2050): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING,
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2050): nl80211: Connect event
D/wpa_supplicant( 2050): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2050): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2050): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2050): wlan0: Association info event
D/wpa_supplicant( 2050): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2050): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2050): wlan0: freq=2412 MHz
D/wpa_supplicant( 2050): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2050): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2050): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2050): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): scard is not null..
D/wpa_supplicant( 2050): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2050): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2050): TDLS: Remove peers on association
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2050): EAPOL: enable timer tick
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): wlan0: Cancelling scan request
,D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :false
D/wpa_supplicant( 2050): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 11 b6 9e 7c 51 dc 72 42 af 73 4a 55 fd 93 92 ...
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2050): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2050): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2050): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2050):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2050):   key_nonce - hexdump(len=32): 11 b6 9e 7c 51 dc 72 42 af 73 4a 55 fd 93 92 71 7a 81 20 ab e2 6f 50 41 d6 e2 d6 5a f5 1f 78 82
D/wpa_supplicant( 2050):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 11 b6 9e 7c 51 dc 72 42 af 73 4a 55 fd 93 92 ...
D/wpa_supplicant( 2050): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2050): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2050): Get randomness: len=32 entropy=4
D/wpa_supplicant( 2050): WPA: Renewed SNonce - hexdump(len=32): f3 a9 43 3e f6 66 49 ad 12 d9 79 3d 72 0f 4d 06 94 59 e0 ae 81 f7 e1 4f 9a d8 fa 8b a9 0e d9 63
,D/wpa_supplicant( 2050): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): WPA: Nonce1 - hexdump(len=32): f3 a9 43 3e f6 66 49 ad 12 d9 79 3d 72 0f 4d 06 94 59 e0 ae 81 f7 e1 4f 9a d8 fa 8b a9 0e d9 63
D/wpa_supplicant( 2050): WPA: Nonce2 - hexdump(len=32): 11 b6 9e 7c 51 dc 72 42 af 73 4a 55 fd 93 92 71 7a 81 20 ab e2 6f 50 41 d6 e2 d6 5a f5 1f 78 82
D/wpa_supplicant( 2050): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2050): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2050): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2050): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2050): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): WPA: Derived Key MIC - hexdump(len=16): eb 4b 15 cd 37 ea 23 dd d5 be 2e 17 cf dd 47 ac
D/wpa_supplicant( 2050): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 f3 a9 43 3e f6 66 49 ad 12 d9 79 3d 72 0f 4d ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 2050): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 11 b6 9e 7c 51 dc 72 42 af 73 4a 55 fd 93 92 ...
D/wpa_supplicant( 2050): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2050): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2050): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2050): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2050):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2050):   key_nonce - hexdump(len=32): 11 b6 9e 7c 51 dc 72 42 af 73 4a 55 fd 93 92 71 7a 81 20 ab e2 6f 50 41 d6 e2 d6 5a f5 1f 78 82
D/wpa_supplicant( 2050):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_rsc - hexdump(len=8): f0 2a 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_mic - hexdump(len=16): 36 95 f5 07 71 75 8d 8d 32 61 98 3b 4f 35 cc 9f
D/wpa_supplicant( 2050): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 11 b6 9e 7c 51 dc 72 42 af 73 4a 55 fd 93 92 ...
D/wpa_supplicant( 2050): RSN: encrypted key data - hexdump(len=56): 16 50 ec f5 0f 54 8e 19 db 74 02 2a 92 27 3e 4c 42 79 c5 7d b0 96 9b b0 88 b8 ac 78 2f 2d 20 11 ...
D/wpa_supplicant( 2050): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2050): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2050): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2050): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 73 0b ...
D/wpa_supplicant( 2050): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2050): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2050): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): WPA: Derived Key MIC - hexdump(len=16): 45 f4 9b 36 c7 e3 c4 04 c0 1b cb 58 4a 64 44 f2
,D/wpa_supplicant( 2050): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2050): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb878cc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2050):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2050): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2050): WPA: Group Key - hexdump(len=16): [REMOVED],
D/wpa_supplicant( 2050): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2050): WPA: RSC - hexdump(len=6): f0 2a 00 00 00 00
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ef403a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2050):    broadcast key
,I/wpa_supplicant( 2050): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2050): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2050): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): wpa_supplicant_set_state, isWPS : 0,
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2050): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2050): EAPOL authentication completed successfully
,D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): Network connection established
,D/WifiNative-wlan0(  965): doString: STATUS
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2050): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/WifiStateMachine(  965): handleMessage: X
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
D/DhcpStateMachine(  965): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-41ms what=147462 obj=android.net.wifi.StateChangeResult@4546c5e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-35ms what=147462 obj=android.net.wifi.StateChangeResult@437850a8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-36ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6269 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 6269): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6269): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6269): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/LGEmail ( 6269): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 6269): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
,D/DhcpStateMachine(  965): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  270): Setting iface cfg
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4369ad30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4369ad30 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Trying to bring up wlan0
D/WifiStateMachine(  965): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
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
,W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  965): send additional Connectivity Action
D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): CaptivePortalCheckState enter
D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  965): handleMessage: X
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  400): Reading a NULL string not supported here.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
V/WfdStateTracker( 1153): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
W/BaseRuntimeLoader( 6269): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6269): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6269): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6269): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6269): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/        (  270): RouteController
,V/        (  270): RouteController
I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = false
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6295 uid=10052 gids={50052, 3003}
W/linker  ( 6269): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 6269): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6269): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 6269): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 6269): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 6269): register_HtmlEditor, Success
D/HtmlEditor( 6269): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6269): register_HtmlEditorTimer, Success
D/HtmlEditor( 6269): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6269): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6269): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6269): register_HtmlEditorFont, Success
D/HtmlEditor( 6269): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6269): register_HtmlEditorDrawText, Success
D/HtmlEditor( 6269): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6269): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6269): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6269): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 6269): JNI_OnLoad Success
I/HubEmail( 6269): JNI_OnLoad()
I/HubEmail( 6269): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6269): registerNatives()
I/HubEmail( 6269): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6269): registerNativeMethods()
I/HubEmail( 6269): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 6269): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/        (  270): RouteController
,I/ActivityManager(  965): Killing 5122:com.lge.wireless_storage/u0a101 (adj 15): empty #17
V/        (  270): RouteController
,V/        (  270): RouteController
D/HyLog   ( 6295): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6295): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6295): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,V/        (  270): RouteController
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
V/LGRssiData( 6295): [loadRssi] File not exist 
V/LGRssiData( 6295): [loadRssi] File not exist 
D/QCNEA   (  400): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  400): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  400): |CAC| updateNetCfgInfo
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC|                   Netconfig               
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  400): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  400): |CAC| 	NetConfig:         fl =21
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
V/QCNEA   (  400): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  400): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  400): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  400): |CAC| 	NetConfig: Default    =true
V/TelephonyAutoProfiling( 6295): [loadFeatureFromXml] *** start feature loading from xml
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| net type = 1
V/QCNEA   (  400): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| Received ssid= NG700
V/QCNEA   (  400): |CAC| 	ssid           =NG700
V/QCNEA   (  400): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  400): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  400): |CAC| dispatchNetCfg: updating:0xb87f38dc
D/QCNEA   (  400): |CAC| readCallback: read len:0, ret:-1, errno:11
W/BaseRuntimeLoader( 6295): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6295): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6295): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6295): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 6295): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6295): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6295): [getValue] FEATURE key : vzw_roaming_state, value : null
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/MobileConnectivityChangeReceiver( 6295): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6295): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 6295): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6295): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6318 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  965): Killing 5135:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1938): Checking schedule, now: 1453391663512 next: 1453390994737
,I/CheckinService( 1938): active receiver: enabled
,D/dalvikvm(  274): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 3ms+5ms, total 43ms
,D/HyLog   ( 6318): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6318): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/CheckinService( 1938): Preparing to send checkin request
,I/EventLogService( 1938): Accumulating logs since 1453390961169
,D/HyLog   ( 6318): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 3ms+3ms, total 29ms
,I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+5ms, total 27ms
,I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6340 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 6340): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6340): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6340): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 4689:com.test.thalitest/u0a304 (adj 15): empty #17
D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6353 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 6353): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6353): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6353): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 6353): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6367 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  965): Killing 5150:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6367): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6367): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6367): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NFS     ( 6367): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,I/Wireless_Storage( 6367): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 6367): intf.getDisplayName() = lo
I/Wireless_Storage( 6367): intf.getDisplayName() = sit0
I/Wireless_Storage( 6367): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6367): intf.getDisplayName() = teql0
I/Wireless_Storage( 6367): intf.getDisplayName() = wlan0
,D/NFS     ( 6367): interface name:wlan0 name:wlan0
D/NFS     ( 6367): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6367): interface name:wlan0 name:wlan0
D/NFS     ( 6367): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 6367): CONNECT : WIFI_CONNECT
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6380 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 5334:com.google.android.talk/u0a77 (adj 15): empty #17
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43495e88: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6380): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6380): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6380): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6392 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6392): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6392): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6392): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6392): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6392): VFY: replacing opcode 0x60 at 0x000b
,W/GAV2    ( 6380): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 6392): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6392): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6392): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6392): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6392): install
,I/MultiDex( 6392): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6392): loading existing secondary dex files
,I/MultiDex( 6392): load found 3 secondary dex files
,I/MultiDex( 6392): install done
,D/dalvikvm( 6392): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 6392): VFY: unable to resolve instance field 61
,D/dalvikvm( 6392): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 6392): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6392): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6392): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 6392): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6392): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6392): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6392): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6392): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6392): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c60730
,D/dalvikvm( 6392): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c60730
,D/dalvikvm( 6392): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c60730, skipping init
,D/dalvikvm( 6392): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c60730
,D/dalvikvm( 6392): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c60730
,V/JNIHelp ( 6392): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 6392): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c60730
,D/dalvikvm( 6392): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42c60730
D/dalvikvm( 6392): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c60730
,D/dalvikvm( 6392): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42c60730
,V/WebViewChromium( 6380): Binding Chromium to the main looper Looper (main, tid 1) {42c594a0}
,I/chromium( 6380): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6380): Initializing chromium process, renderers=0
,D/wpa_supplicant( 2050): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2050): EAPOL: disable timer tick
,W/chromium( 6380): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6380): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6380): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6380): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6380): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6380): Remote Branch: 
I/Adreno-EGL( 6380): Local Patches: 
I/Adreno-EGL( 6380): Reconstruct Branch: 
,I/ProviderInstaller( 6392): Installed default security provider GmsCore_OpenSSL
,I/NSApplication( 6380): Starting up...
I/dalvikvm( 6392): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6392): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6392): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6392): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6392): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6392): VFY: replacing opcode 0x6e at 0x0201
,I/ActivityManager(  965): Killing 5384:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2a000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2a000
I/ActivityManager(  965): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=6432 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/HyLog   ( 6432): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6432): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6432): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/dalvikvm( 6432): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c60be8
D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=972798483
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/dalvikvm( 6432): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c60be8
,D/jxcore_app_log( 6432): JniHelper::setJavaVM(0x41c0c808), pthread_self() = 1073930580
,E/JX-Cordova( 6432): JXcore wasn't initialized yet
,D/QRemote ( 6227): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6227): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6227): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6227): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6227): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/dalvikvm( 6392): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e412d8
D/dalvikvm( 6392): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e412d8
,D/dalvikvm( 6392): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e412d8, skipping init
,I/QRemote ( 6227): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6185): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6185): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6227): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6227): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6227): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6227): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  965): Killing 5399:com.android.gallery3d/u0a27 (adj 15): empty #17
D/AuthorizationBluetoothService( 1547): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1547): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/WearableService( 1834): callingUid 10006, callindPid: 1834
,E/MDM     ( 1422): [73] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1938): Restart initialization of location
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  965): Skipping unknown process pid 6261
,W/ProcessCpuTracker(  965): Skipping unknown process pid 6264
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
D/WVCdm   (  276): PrepareKeyRequest: nonce=3162383650
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/dalvikvm(  965): GC_EXPLICIT freed 2823K, 49% free 30648K/59276K, paused 4ms+11ms, total 146ms
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/dalvikvm( 6392): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/dalvikvm( 6460): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 6392): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6392): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 85ms
,I/Adreno-EGL( 6392): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6392): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6392): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6392): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6392): Remote Branch: 
I/Adreno-EGL( 6392): Local Patches: 
I/Adreno-EGL( 6392): Reconstruct Branch: 
,I/Adreno-EGL( 6392): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6392): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6392): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6392): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6392): Remote Branch: 
I/Adreno-EGL( 6392): Local Patches: 
I/Adreno-EGL( 6392): Reconstruct Branch: 
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
,I/Adreno-EGL( 6392): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6392): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6392): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6392): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6392): Remote Branch: 
I/Adreno-EGL( 6392): Local Patches: 
I/Adreno-EGL( 6392): Reconstruct Branch: 
,W/Settings( 6392): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/NativeCrypto( 1938): SSL shutdown failed: ssl=0x6ce5c4c8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1938): SSL shutdown failed: ssl=0x6ce7fba0: I/O error during system call, Connection timed out
,I/CheckinTask( 1938): Sending checkin request (11466 bytes)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
,D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
,D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4077): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4077): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4077): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4077): handleAsync isTriedOnce : false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,E/AppUp4:CustModeStarterReceiver( 4077): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5451): DownloadService onCreate
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6269): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6295): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6295): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6353): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6367): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6367): CONNECT : WIFI_CONNECT
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 5451): in removeSpuriousFiles
,V/DownloadManager( 5451): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/Settings( 6269): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cad030 on behalf of 5451
,I/DownloadManager( 5451): in trimDatabase
,V/DownloadManager( 5451): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5451): DownloadService onStartCommand
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 5451): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cb0708 on behalf of 5451
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42caee78 on behalf of 5451
,V/DownloadManager( 5451): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5451): DownloadService onCreate
,I/DownloadManager( 5451): in removeSpuriousFiles
V/DownloadManager( 5451): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cb5318 on behalf of 5451
,I/DownloadManager( 5451): in trimDatabase
,V/DownloadManager( 5451): DownloadService onStartCommand
,V/DownloadManager( 5451): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5451): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cb7cc0 on behalf of 5451
I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4375): networkInfo.isConnected() = true
,D/PhoneState( 4375): setPdpRejectCasuse : false
,W/Settings( 6269): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cb9208 on behalf of 5451
,D/MobileConnectivityChangeReceiver( 6295): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6295): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5451): DownloadService onDestroy
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6353): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 6367): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6367): CONNECT : WIFI_CONNECT
,W/ContextImpl( 6353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1547): GC_EXPLICIT freed 1494K, 28% free 17980K/24832K, paused 2ms+6ms, total 55ms
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,D/GCM     ( 1547): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1547): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x437d0e70: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,I/CheckinTask( 1938): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1938): Checking schedule, now: 1453391667469 next: 1453969063465
,I/CheckinService( 1938): active receiver: disabled
,I/CheckinService( 1938): Checking schedule, now: 1453391667498 next: 1453969063465
,I/CheckinService( 1938): active receiver: disabled
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
,D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5451): DownloadService onCreate
,D/EAS     ( 6269): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = true
,D/PhoneState( 4375): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6295): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6295): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
,D/LGDMSGCM( 6353): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/ContextImpl( 6353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6367): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6367): CONNECT : WIFI_CONNECT
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/Settings( 6269): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 5451): in removeSpuriousFiles
,V/DownloadManager( 5451): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cbd808 on behalf of 5451
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 5451): DownloadService onStartCommand
,V/DownloadManager( 5451): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5451): in trimDatabase
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5451): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cbfd50 on behalf of 5451
V/DownloadManager( 5451): created cursor android.database.sqlite.SQLiteCursor@42cc0bc0 on behalf of 5451
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 5451): DownloadService onDestroy
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/GAV2    ( 6380): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  965): Killing 6185:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): Killing 5417:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3820): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3820): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  965): Handling package changes for user 0
,I/[LGHome]Launcher( 1485): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6576 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1139): changeTargets() succeeded. size: 20
,D/HyLog   ( 6576): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6576): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6576): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
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
,I/MediaCodecList( 6576): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 6576): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6576): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 6576): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Babel   ( 6576): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6576): MmsConfig.loadMmsSettings
I/Babel   ( 6576): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6576): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 6576): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6576): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/GmsNetworkLocationProvi( 1422): DISABLE
W/BaseRuntimeLoader( 6576): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6576): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6576): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6576): MmsConfig.loadFromResources
,E/Babel   ( 6576): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6576): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
,W/Settings( 6576): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6576): [loadRssi] File not exist 
V/LGRssiData( 6576): [loadRssi] File not exist 
D/AppUp4:Utils( 4077): [getPackageName] uri : package:com.google.android.gms
V/TelephonyAutoProfiling( 6576): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4  ( 4077): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4077): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
D/AppUp4:CustFacade( 4077): isPhone : true
,V/TelephonyAutoProfiling( 6576): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6576): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6576): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
D/AppUp4:Utils( 4077): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4077): Event For Nothing, skip.
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6624 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6624): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6624): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6624): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6624): BUILD Country: EU
,I/SystemConfig( 6624): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 6227:com.lge.qremote/u0a96 (adj 15): empty #17
I/ActivityManager(  965): Killing 5451:android.process.media/u0a23 (adj 15): empty #17
,I/SystemConfig( 6624): systemFeature RCS result false
,D/SystemConfig( 6624): refreshRcsSupport() :false
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6638 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6638): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6638): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6638): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 6269:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2672): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  965): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6657 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6657): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6657): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6657): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  965): GC_EXPLICIT freed 2376K, 49% free 30732K/59276K, paused 3ms+12ms, total 132ms
,I/dalvikvm( 6657): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6657): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6657): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6657): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6657): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6657): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6657): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6657): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6657): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6657): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6657): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6657): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6657): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6657): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/IcingCorporaProvider( 2672): UpdateCorporaTask done [took 450 ms] updated apps [took 450 ms] 
,I/dalvikvm( 6657): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6657): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6657): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6657): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,I/ActivityManager(  965): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6698 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
W/dalvikvm( 6657): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6657): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6657): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6657): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
D/dalvikvm( 6657): VFY: replacing opcode 0x6e at 0x029a
,D/HyLog   ( 6698): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6698): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6698): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 30ms
,I/dalvikvm( 6657): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 6657): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6657): VFY: replacing opcode 0x6e at 0x001a
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,I/dalvikvm( 6657): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 6657): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6657): VFY: replacing opcode 0x6e at 0x0049
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,D/Finsky  ( 6657): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6657): [1] 2.run: Finished loading 1 libraries.
,V/DownloadManager( 6698): DownloadService onCreate
,I/DownloadManager( 6698): in removeSpuriousFiles
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42ca22d0 on behalf of 6657
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42ca4ad0 on behalf of 6698
,I/PackageBroadcastService( 1938): Null package name or gms related package.  Ignoreing.
,I/DownloadManager( 6698): in trimDatabase
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42ca7b50 on behalf of 6698
,V/DownloadManager( 6698): DownloadService onStartCommand
,I/Icing   ( 1938): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6698): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 6657): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42caaa18 on behalf of 6698
,V/DownloadManager( 6698): DownloadService onDestroy
,D/Finsky  ( 6657): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  965): Killing 6295:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm( 1938): GC_CONCURRENT freed 1996K, 22% free 19566K/24832K, paused 8ms+5ms, total 50ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6657): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6657): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6657): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6657): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6657): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391675987050193; DSPS: 29200819; Offset: 1453390784848775047
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6657): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6657): Total arena pages for JIT: 11
,I/dalvikvm( 6657): Total arena pages for JIT: 12
I/dalvikvm( 6657): Total arena pages for JIT: 13
,I/dalvikvm( 6657): Total arena pages for JIT: 14
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6657): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6657): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6657): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6657): [1] DailyHygiene.reschedule: Scheduling new run in 254 minutes (failures=4)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  965): Checking http://216.58.198.142/generate_204
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6576): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  965): Killing 6318:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 6657): [519] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6657): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391695987952935; DSPS: 29856208; Offset: 1453390784848792779
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391700031, nextTick: 59999, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391700052, nextTick: 59975, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391715988884693; DSPS: 30511599; Offset: 1453390784848778492
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391735989325018; DSPS: 31166973; Offset: 1453390784848791571
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391755990250750; DSPS: 31822364; Offset: 1453390784848771258
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391760034, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391760045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391775991183307; DSPS: 32477754; Offset: 1453390784848788288
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391795991630779; DSPS: 33133129; Offset: 1453390784848777996
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391815992493167; DSPS: 33788517; Offset: 1453390784848785892
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391820045, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391820047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391835995397421; DSPS: 34443972; Offset: 1453390784848790976
,D/wpa_supplicant( 2050): wlan0: BSS: Remove id 10 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Remove id 11 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391855995822764; DSPS: 35099346; Offset: 1453390784848789073
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391875996693423; DSPS: 35754735; Offset: 1453390784848774722
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391880034, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391880046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391895997607499; DSPS: 36410125; Offset: 1453390784848773271
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391915998048074; DSPS: 37065499; Offset: 1453390784848786600
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391935998912519; DSPS: 37720888; Offset: 1453390784848766035
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391940045, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453391940049, nextTick: 59982, mDrawingTime: 1
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2050): nl80211: Disconnect event
D/wpa_supplicant( 2050): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2050): wlan0: Deauthentication notification
D/wpa_supplicant( 2050): wlan0:  * reason 0
D/wpa_supplicant( 2050): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2050): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2050): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2050): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2050): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2050): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2050): wlan0: Disconnect event - remove keys
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  965): handleMessage: E msg.what=147460
,D/WifiStateMachine(  965): processMsg: ConnectedState,
D/WifiStateMachine(  965): processMsg: L2ConnectedState,
D/WifiStateMachine(  965): processMsg: ConnectModeState,
D/WifiStateMachine(  965): Network connection lost,
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true,
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
,D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb878bd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2050):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2050): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5,
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
,D/DhcpStateMachine(  965): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine(  965): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
D/QCNEA   (  400): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  400): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  400): |CAC| updateNetCfgInfo
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC|                   Netconfig               
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  400): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  400): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  400): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  400): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  400): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  400): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| Received bssid= 
D/QCNEA   (  400): |CAC| net type = 3
V/QCNEA   (  400): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  400): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  400): |CAC| 	ssid           =NG700
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  400): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  400): |CAC| dispatchNetCfg: updating:0xb87f38dc
D/QCNEA   (  400): |CAC| readCallback: read len:0, ret:-1, errno:11
D/wpa_supplicant( 2050): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2050): wlan0: nl80211: scan request
,D/wpa_supplicant( 2050): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiHS20(  965): hidePasspointNotification off =false
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2050): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2050): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,V/WfdStateTracker( 1153): handleWifiStateChangedEvent: 0
D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '95 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 95 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
,I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6984 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '96 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 96 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '97 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 97 Failed to remove route from default table (No such process)'
V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6984): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6984): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6984): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
W/NetworkManagementService(  965): route cmd failed: 
W/NetworkManagementService(  965): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '99 route del src v6 2' failed with '400 99 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  965): android_net_utils_resetConnections in env=0x628242c0 clazz=0x700001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  965): resetConnections(wlan0, 3)
I/PCSuite ( 6984): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6984): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6984): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7027 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  965): Killing 6340:com.lge.drmservice/u0a66 (adj 15): empty #17
V/NativeCrypto( 1547): Read error: ssl=0x63931d18: I/O error during system call, Connection timed out
V/NativeCrypto( 1547): SSL shutdown failed: ssl=0x63931d18: I/O error during system call, Broken pipe
,D/DhcpStateMachine(  965): StoppedState
,D/HyLog   ( 7027): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7027): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7027): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 7027): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/QRemote ( 7027): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 7027): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/QRemote ( 7027): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7027): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7027): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7027): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7027): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7027): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 6353:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2050): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2050): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2050): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2050): nl80211: Survey data missing
D/wpa_supplicant( 2050): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 12 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: BSS: Add new id 13 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2050): wlan0: New scan results available
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2050): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2050): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2050): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2050): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2050): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47 wps
D/wpa_supplicant( 2050): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2050): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2050): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2050): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2050): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2050): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2050): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47 wps
D/wpa_supplicant( 2050): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2050): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2050): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb878d5a8  current_ssid=0x0
D/wpa_supplicant( 2050): scard is not null..
D/wpa_supplicant( 2050): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2050): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2050): wlan0: [MDM] lg_mdm_auto_co,nnect_policy 0
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2050): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2050): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2050): wlan0: Cancelling scan request
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2050): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2050): RSN: PMKSA cache search - network_ctx=0xb878d5a8 try_opportunistic=0
D/wpa_supplicant( 2050): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2050): RSN: No PMKSA cache entry found,
D/wpa_supplicant( 2050): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2050): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2050): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2050): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2050): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2050): wlan0: WPA: using PTK CCMP,
D/wpa_supplicant( 2050): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2050): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2050): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2050): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2050): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2050): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2050): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2050): nl80211: Unsubscribe mgmt frames handle 0xb878c590 (mode change)
D/wpa_supplicant( 2050): nl80211: Subscribe to mgmt frames with non-AP handle 0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0a,
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590,
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
,D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
,D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 04 0e
,D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 2050): nl80211: Register frame type=0xd0 nl_handle=0xb878c590
D/wpa_supplicant( 2050): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2050): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2050):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050):   * freq=2412
D/wpa_supplicant( 2050):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2050):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050):   * Auth Type 0,
D/wpa_supplicant( 2050):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 38:f8:89:11:e9:11]
,D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/wpa_supplicant( 2050): nl80211: Connect request send successfully
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2050): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :false
D/wpa_supplicant( 2050): nl80211: Event message available
D/wpa_supplicant( 2050): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2050): nl80211: Connect event
D/wpa_supplicant( 2050): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2050): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2050): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2050): wlan0: Association info event
D/wpa_supplicant( 2050): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2050): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2050): wlan0: freq=2412 MHz
D/wpa_supplicant( 2050): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2050): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2050): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2050): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): scard is not null..
D/wpa_supplicant( 2050): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2050): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2050): TDLS: Remove peers on association
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2050): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2050): EAPOL: enable timer tick
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): wlan0: Cancelling scan request
,D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
,D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
D/wpa_supplicant( 2050): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1a 3e 54 bb 74 e2 6a 58 0a b2 f6 25 e8 9a 94 ...
D/wpa_supplicant( 2050): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2050): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2050): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2050): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2050): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2050):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2050):   key_nonce - hexdump(len=32): 1a 3e 54 bb 74 e2 6a 58 0a b2 f6 25 e8 9a 94 e2 27 bd 41 17 83 f8 91 2d 5f 8c 20 56 78 43 ee 93
D/wpa_supplicant( 2050):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 1a 3e 54 bb 74 e2 6a 58 0a b2 f6 25 e8 9a 94 ...
D/wpa_supplicant( 2050): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2050): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2050): Get randomness: len=32 entropy=4
D/wpa_supplicant( 2050): WPA: Renewed SNonce - hexdump(len=32): a4 d9 61 53 4a 4d cd 0a 9d f9 97 4e f2 cb 63 61 54 db e9 b7 88 85 3a 85 13 a2 94 08 e3 89 5e f5
D/wpa_supplicant( 2050): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): WPA: Nonce1 - hexdump(len=32): a4 d9 61 53 4a 4d cd 0a 9d f9 97 4e f2 cb 63 61 54 db e9 b7 88 85 3a 85 13 a2 94 08 e3 89 5e f5
D/wpa_supplicant( 2050): WPA: Nonce2 - hexdump(len=32): 1a 3e 54 bb 74 e2 6a 58 0a b2 f6 25 e8 9a 94 e2 27 bd 41 17 83 f8 91 2d 5f 8c 20 56 78 43 ee 93
D/wpa_supplicant( 2050): WPA: PMK - hexdump(len=32): [REMOVED]
,D/wpa_supplicant( 2050): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2050): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2050): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2050): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2050): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): WPA: Derived Key MIC - hexdump(len=16): 6d 52 7a 9f 7c be 60 c9 97 54 8d 72 f5 5a c3 49
,D/wpa_supplicant( 2050): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 a4 d9 61 53 4a 4d cd 0a 9d f9 97 4e f2 cb 63 ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/SIMObserver( 2987): simInfo1
D/wpa_supplicant( 2050): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2050): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1a 3e 54 bb 74 e2 6a 58 0a b2 f6 25 e8 9a 94 ...
D/wpa_supplicant( 2050): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2050): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2050): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2050): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2050):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2050):   key_nonce - hexdump(len=32): 1a 3e 54 bb 74 e2 6a 58 0a b2 f6 25 e8 9a 94 e2 27 bd 41 17 83 f8 91 2d 5f 8c 20 56 78 43 ee 93
D/wpa_supplicant( 2050):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_rsc - hexdump(len=8): a1 2b 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2050):   key_mic - hexdump(len=16): 0c 98 29 32 ad a1 e4 10 29 6e 8b 26 1d 11 b1 ee
D/wpa_supplicant( 2050): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 1a 3e 54 bb 74 e2 6a 58 0a b2 f6 25 e8 9a 94 ...
D/wpa_supplicant( 2050): RSN: encrypted key data - hexdump(len=56): 91 af 54 0d a5 66 f5 0c 72 ff d0 65 88 98 9a 35 ed 45 b0 6d cf cf fd 92 bf 6c 94 13 85 04 86 a2 ...
D/wpa_supplicant( 2050): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2050): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2050): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2050): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 73 0b ...
D/wpa_supplicant( 2050): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2050): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2050): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2050): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): WPA: Derived Key MIC - hexdump(len=16): 87 c9 0e b0 aa 70 cb 83 15 e1 e2 28 3f 1a 4e af
,D/wpa_supplicant( 2050): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2050): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb878cc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2050):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2050): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2050): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2050): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2050): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
,D/wpa_supplicant( 2050): WPA: RSC - hexdump(len=6): a1 2b 00 00 00 00,
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ef403a key_idx=1 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 2050):    broadcast key
I/wpa_supplicant( 2050): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2050): wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
I/wpa_supplicant( 2050): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 2050): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2050): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2050): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2050): EAPOL: External notification - portValid=1,
D/wpa_supplicant( 2050): EAPOL: External notification - EAP success=1,
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2050): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2050): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2050): EAPOL: Supplicant port status: Authorized,
D/wpa_supplicant( 2050): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2050): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2050): EAPOL authentication completed successfully
D/wpa_supplicant( 2050): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2050): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2050): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): Network connection established
,D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2050): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2050): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
,I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  965): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity
D/WifiStateMachine(  965): ObtainingIpState{ when=-31ms what=147462 obj=android.net.wifi.StateChangeResult@436c3180 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@44a73418 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-28ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/ActivityManager(  965): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7074 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 7074): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7074): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7074): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 0
,D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
,E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
D/WifiP2pService(  965): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4369ad30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4369ad30 target=com.android.internal.util.StateMachine$SmHandler }
I/LGEmail ( 7074): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/CommandListener(  270): Setting iface cfg
D/CommandListener(  270): Trying to bring up wlan0
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2050): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2050): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2050): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2050): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2050): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2050): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): DHCP successful
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  965): send additional Connectivity Action
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  400): Reading a NULL string not supported here.
E/Parcel  (  400): Reading a NULL string not supported here.
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
E/Parcel  (  400): Reading a NULL string not supported here.
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
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
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/BubblePopupHelper( 1139): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,E/Parcel  (  400): Reading a NULL string not supported here.
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardUpdateMonitor( 1139): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1153): handleWifiStateChangedEvent: 1
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1139): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
,E/Parcel  (  400): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
D/LGEmail ( 7074): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,W/BaseRuntimeLoader( 7074): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7074): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7074): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7074): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/QCNEA   (  400): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  400): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  400): |CAC| updateNetCfgInfo
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC|                   Netconfig               
V/QCNEA   (  400): |CAC| *********************************************
V/QCNEA   (  400): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  400): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  400): |CAC| 	NetConfig:         fl =21
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  400): |CAC| 	NetConfig: ip4        =192.168.1.155
V/QCNEA   (  400): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  400): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  400): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| net type = 1
V/QCNEA   (  400): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  400): |CAC| Received ssid= NG700
V/QCNEA   (  400): |CAC| 	ssid           =NG700
V/QCNEA   (  400): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  400): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  400): |CAC| *********************************************
D/QCNEA   (  400): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  400): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  400): |CAC| dispatchNetCfg: updating:0xb87f38dc
,D/QCNEA   (  400): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/eas_req ( 7074): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  965): GC_EXPLICIT freed 1971K, 49% free 30691K/59276K, paused 4ms+13ms, total 170ms
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = false
,W/linker  ( 7074): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 7074): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 7074): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 7074): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 7074): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 7074): register_HtmlEditor, Success
,D/HtmlEditor( 7074): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 7074): register_HtmlEditorTimer, Success
D/HtmlEditor( 7074): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 7074): register_HtmlEditorDownloader, Success
,D/HtmlEditor( 7074): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7074): register_HtmlEditorFont, Success
D/HtmlEditor( 7074): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 7074): register_HtmlEditorDrawText, Success
D/HtmlEditor( 7074): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 7074): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 7074): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 7074): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 7074): JNI_OnLoad Success
,I/HubEmail( 7074): JNI_OnLoad()
I/HubEmail( 7074): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7074): registerNatives()
I/HubEmail( 7074): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7074): registerNativeMethods()
,I/HubEmail( 7074): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 7074): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=7122 uid=10052 gids={50052, 3003}
,I/ActivityManager(  965): Killing 6367:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/HyLog   ( 7122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7122): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7122): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 7122): [loadRssi] File not exist 
,V/LGRssiData( 7122): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7122): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 7122): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7122): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 7122): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/BaseRuntimeLoader( 7122): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 7122): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 7122): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 7122): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7122): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7122): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7137 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 7122): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 7122): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  965): Killing 6380:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,I/CheckinService( 1938): Checking schedule, now: 1453391947096 next: 1453391697465
,I/CheckinService( 1938): active receiver: enabled
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7137): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7137): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7137): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1938): Preparing to send checkin request
,I/EventLogService( 1938): Accumulating logs since 1453391663543
,I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7151 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 7151): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7151): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7151): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  965): Killing 6432:com.test.thalitest/u0a304 (adj 15): empty #17
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=7164 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 7164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7164): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 7164): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=7176 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  965): Killing 6392:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 7176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7176): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7176): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NFS     ( 7176): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Wireless_Storage( 7176): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 7176): intf.getDisplayName() = lo
I/Wireless_Storage( 7176): intf.getDisplayName() = sit0
I/Wireless_Storage( 7176): intf.getDisplayName() = p2p0
I/Wireless_Storage( 7176): intf.getDisplayName() = teql0
I/Wireless_Storage( 7176): intf.getDisplayName() = wlan0
D/NFS     ( 7176): interface name:wlan0 name:wlan0
,D/NFS     ( 7176): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 7176): interface name:wlan0 name:wlan0
D/NFS     ( 7176): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 7176): CONNECT : WIFI_CONNECT
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7196 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 6576:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
D/wpa_supplicant( 2050): EAPOL: startWhen --> 0
D/wpa_supplicant( 2050): EAPOL: disable timer tick
,D/HyLog   ( 7196): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7196): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7196): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x436e2880: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7209 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,W/GAV2    ( 7196): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/HyLog   ( 7209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7209): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7209): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 7209): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7209): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 7209): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7209): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7209): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 7209): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7209): install
,I/MultiDex( 7209): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 7209): loading existing secondary dex files
,I/MultiDex( 7209): load found 3 secondary dex files
,I/MultiDex( 7209): install done
,D/dalvikvm( 7209): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 7209): VFY: unable to resolve instance field 61
,D/dalvikvm( 7209): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 7209): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7209): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7209): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 7209): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7209): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7209): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 7209): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7209): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 7209): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c65648
,D/dalvikvm( 7209): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c65648
,D/dalvikvm( 7209): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c65648, skipping init
,D/dalvikvm( 7209): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c65648
,D/dalvikvm( 7209): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c65648
,V/JNIHelp ( 7209): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 7196): Binding Chromium to the main looper Looper (main, tid 1) {42c5e498}
,I/chromium( 7196): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7196): Initializing chromium process, renderers=0
,D/dalvikvm( 7209): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42c65648
,D/dalvikvm( 7209): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42c65648
D/dalvikvm( 7209): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42c65648
,D/dalvikvm( 7209): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42c65648
,W/chromium( 7196): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 7196): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7196): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7196): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7196): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7196): Remote Branch: 
I/Adreno-EGL( 7196): Local Patches: 
I/Adreno-EGL( 7196): Reconstruct Branch: 
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
,I/NSApplication( 7196): Starting up...
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ProviderInstaller( 7209): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 3989): GC_FOR_ALLOC freed 388K, 2% free 37786K/38444K, paused 20ms, total 22ms
I/ActivityManager(  965): Killing 6624:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm( 1547): GC_EXPLICIT freed 1360K, 28% free 17988K/24832K, paused 2ms+6ms, total 43ms
,I/ActivityManager(  965): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=7249 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/HyLog   ( 7249): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7249): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7249): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 30ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 23ms
,I/dalvikvm( 7209): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 7209): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7209): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7209): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/dalvikvm( 7209): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 7209): VFY: replacing opcode 0x6e at 0x0201
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 7249): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c65b00
,D/dalvikvm( 7249): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42c65b00
D/jxcore_app_log( 7249): JniHelper::setJavaVM(0x41c0c808), pthread_self() = 1073930580
,E/JX-Cordova( 7249): JXcore wasn't initialized yet
,D/QRemote ( 7027): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7027): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 7027): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7027): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 7027): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7027): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6984): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6984): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 7027): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7027): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 7027): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7027): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
I/ActivityManager(  965): Killing 6638:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2a000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e2a000
,D/AuthorizationBluetoothService( 1547): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1547): Proximity feature is not enabled.
D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/WearableService( 1834): callingUid 10006, callindPid: 1834
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/LocationInitializer( 1938): Restart initialization of location
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,E/MDM     ( 1422): [74] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=3052919275
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/dalvikvm( 7209): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e16650
D/dalvikvm( 7209): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e16650
,D/dalvikvm( 7209): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42e16650, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
,D/GCM     ( 1547): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1547): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=21298535
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 7209): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 7309): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 7209): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7209): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 106ms
,I/Adreno-EGL( 7209): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7209): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7209): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7209): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7209): Remote Branch: 
I/Adreno-EGL( 7209): Local Patches: 
I/Adreno-EGL( 7209): Reconstruct Branch: 
,I/Adreno-EGL( 7209): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7209): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7209): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7209): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7209): Remote Branch: 
I/Adreno-EGL( 7209): Local Patches: 
I/Adreno-EGL( 7209): Reconstruct Branch: 
,I/Adreno-EGL( 7209): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7209): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 7209): Build Date: 01/20/14 Mon
I/Adreno-EGL( 7209): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 7209): Remote Branch: 
I/Adreno-EGL( 7209): Local Patches: 
I/Adreno-EGL( 7209): Reconstruct Branch: 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 7209): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
,D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4077): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4077): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4077): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4077): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4077): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 6698): DownloadService onCreate
,I/DownloadManager( 6698): in removeSpuriousFiles
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cb1bd8 on behalf of 6698
,D/eas_req ( 7074): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 6698): in trimDatabase
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6698): DownloadService onStartCommand
,V/DownloadManager( 6698): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinTask( 1938): Sending checkin request (11471 bytes)
I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = false
W/Settings( 7074): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cb4250 on behalf of 6698
,D/MobileConnectivityChangeReceiver( 7122): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/MobileConnectivityChangeReceiver( 7122): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cb5728 on behalf of 6698
D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 6698): DownloadService onDestroy
D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 7164): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 7176): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7176): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,W/ContextImpl( 7164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
,D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6698): DownloadService onCreate
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 6698): in removeSpuriousFiles
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cb9e60 on behalf of 6698
,I/DownloadManager( 6698): in trimDatabase
,V/DownloadManager( 6698): DownloadService onStartCommand
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6698): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cbbf50 on behalf of 6698
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cbd078 on behalf of 6698
,I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = true
,D/PhoneState( 4375): setPdpRejectCasuse : false
,W/Settings( 7074): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 7122): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7122): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 6698): DownloadService onDestroy
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMSGCM( 7164): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,I/NFS     ( 7176): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 7176): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4077): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
,D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4077): begin check event
,I/AppUp4:CustModeStarterReceiver( 4077): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6698): DownloadService onCreate
,D/EAS     ( 7074): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4375): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4375): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4375): networkInfo.isConnected() = true
,D/PhoneState( 4375): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 7122): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7122): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 7164): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 7176): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 7176): CONNECT : WIFI_CONNECT
,W/Settings( 7074): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 6698): in removeSpuriousFiles
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cc16f0 on behalf of 6698
,I/DownloadManager( 6698): in trimDatabase
,V/DownloadManager( 6698): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cc2d98 on behalf of 6698
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 6698): DownloadService onStartCommand
,D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 6698): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,V/DownloadManager( 6698): created cursor android.database.sqlite.SQLiteCursor@42cc52b0 on behalf of 6698
,V/DownloadManager( 6698): DownloadService onDestroy
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/dalvikvm(  965): GC_EXPLICIT freed 1562K, 49% free 30736K/59276K, paused 6ms+10ms, total 154ms
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x431b9760: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,I/CheckinTask( 1938): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1938): Checking schedule, now: 1453391951857 next: 1453969347854
,I/CheckinService( 1938): active receiver: disabled
,I/CheckinService( 1938): Checking schedule, now: 1453391951892 next: 1453969347854
,I/CheckinService( 1938): active receiver: disabled
,D/GCM     ( 1547): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,D/BubblePopupHelper( 1139): isShowingBubblePopup : false
,I/GAV2    ( 7196): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  965): Killing 6984:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): Killing 6657:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391956000329234; DSPS: 38376294; Offset: 1453390784848778942
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3820): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3820): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  965): Handling package changes for user 0
,I/[LGHome]Launcher( 1485): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=7407 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 7407): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7407): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7407): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  965): getAssistContextExtras failed: no resumed activity
,D/GlobalAccess( 1139): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1139): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1422): DISABLE
I/Babel   ( 7407): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 7407): MmsConfig.loadMmsSettings
,I/MediaCodecList( 7407): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 7407): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 7407): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 7407): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Babel   ( 7407): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 7407): MmsConfig.loadFromDatabase
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/BaseRuntimeLoader( 7407): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7407): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7407): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7407): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 7407): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7407): MmsConfig.loadFromResources
,E/Babel   ( 7407): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7407): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 7407): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
V/LGRssiData( 7407): [loadRssi] File not exist 
,V/LGRssiData( 7407): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7407): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 4077): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4077): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4077): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/TelephonyAutoProfiling( 7407): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7407): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7407): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4077): onReceive
D/AppUp4:CustFacade( 4077): Context : android.app.ReceiverRestrictedContext@42c76288
D/AppUp4:CustFacade( 4077): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4077): isOpenOperator : true
,D/AppUp4:CustFacade( 4077): isPhone : true
,I/LicenseContentProvider( 2987): start selecting data
,D/SIMObserver( 2987): simInfo1
,I/AppUp4:EulaManager( 4077): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4077): begin check event
D/AppUp4:Utils( 4077): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4077): Event For Nothing, skip.
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7457 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 7457): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7457): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7457): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 7457): BUILD Country: EU
,I/SystemConfig( 7457): BUILD Operator: OPEN
,I/SystemConfig( 7457): systemFeature RCS result false
,D/SystemConfig( 7457): refreshRcsSupport() :false
I/ActivityManager(  965): Killing 7027:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7480 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): Killing 6698:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7480): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7480): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7480): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 7074:com.lge.email/u0a24 (adj 15): empty #17
I/IcingCorporaProvider( 2672): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7498 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 7498): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7498): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7498): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 7498): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 7498): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7498): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 7498): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7498): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 7498): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7498): VFY: replacing opcode 0x6e at 0x004f
,I/IcingCorporaProvider( 2672): UpdateCorporaTask done [took 315 ms] updated apps [took 314 ms] 
,W/BaseRuntimeLoader( 7498): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7498): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7498): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7498): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7498): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7498): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7498): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7498): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 7498): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7498): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 7498): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7498): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 7498): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7498): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 7498): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7498): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 7498): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 7498): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7498): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  965): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7535 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 7535): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7535): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7535): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 7498): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 7498): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7498): VFY: replacing opcode 0x6e at 0x0049
,D/dalvikvm( 1547): null clazz in OP_INSTANCE_OF, single-stepping
,D/Finsky  ( 7498): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7498): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1938): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1938): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 7535): DownloadService onCreate
,I/DownloadManager( 7535): in removeSpuriousFiles
,V/DownloadManager( 7535): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7535): DownloadService onStartCommand
,V/DownloadManager( 7535): created cursor android.database.sqlite.SQLiteCursor@42c9c800 on behalf of 7535
,V/DownloadManager( 7535): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 7535): in trimDatabase
,V/DownloadManager( 7535): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 7535): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7535): created cursor android.database.sqlite.SQLiteCursor@42ca0de0 on behalf of 7535
,V/DownloadManager( 7535): created cursor android.database.sqlite.SQLiteCursor@42ca2ee0 on behalf of 7535
,V/DownloadManager( 7535): created cursor android.database.sqlite.SQLiteCursor@42ca4608 on behalf of 7498
,V/DownloadManager( 7535): DownloadService onDestroy
,I/ActivityManager(  965): Killing 7122:com.google.android.setupwizard/u0a52 (adj 15): empty #17
D/Finsky  ( 7498): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 7498): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7498): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7498): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7498): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7498): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7498): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm(  965): GC_EXPLICIT freed 2357K, 49% free 30811K/59276K, paused 7ms+14ms, total 198ms
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7498): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 7498): Total arena pages for JIT: 11
,I/dalvikvm( 7498): Total arena pages for JIT: 12
I/dalvikvm( 7498): Total arena pages for JIT: 13
,I/dalvikvm( 7498): Total arena pages for JIT: 14
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1547): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7498): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7498): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7498): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7498): [1] DailyHygiene.reschedule: Scheduling new run in 854 minutes (failures=5)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 7407): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  965): Killing 7137:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{430489f0 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 7498): [567] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7498): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391976000778306; DSPS: 39031669; Offset: 1453390784848770250
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453391996001228713; DSPS: 39687043; Offset: 1453390784848793411
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453392000056, nextTick: 59975, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453392000060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453392016002168857; DSPS: 40342434; Offset: 1453390784848787510
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453392036002627439; DSPS: 40997809; Offset: 1453390784848788328
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453392056003063409; DSPS: 41653183; Offset: 1453390784848797052
,D/KeyguardUpdateMonitor( 1139): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1139): handleTimeUpdate
,D/KeyguardModel( 1139): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453392060039, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1139): Clock updated, drawingStartTime : 1453392060042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453392076004594287; DSPS: 42308594; Offset: 1453390784848771534
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1453392096005046413; DSPS: 42963968; Offset: 1453390784848796413
,TIME-OUT KILL (timeout was 1200000ms)
```
