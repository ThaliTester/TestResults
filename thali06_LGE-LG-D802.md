#### Test 564496600f5d794_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4532): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  967): Killing 3901:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43988c38 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1946): GC_CONCURRENT freed 1535K, 22% free 19449K/24832K, paused 1ms+3ms, total 33ms
I/ConfigFetchService( 1946): fetch service done; releasing wakelock
I/ConfigFetchService( 1946): stopping self
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
D/AndroidRuntime( 4575): 
D/AndroidRuntime( 4575): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4575): CheckJNI is OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/dalvikvm( 4575): Trying to load lib libjavacore.so 0x0
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/dalvikvm( 4575): Added shared lib libjavacore.so 0x0
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/dalvikvm( 4575): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4575): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4575): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/WifiController(  967): battery changed pluggedType: 2
D/dalvikvm( 4575): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4575): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4575): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1946): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4575): Calling main entry com.android.commands.am.Am
D/Icing   ( 1946): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4575
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43988c38 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (104 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  967): GC_FOR_ALLOC freed 24236K, 52% free 28838K/59892K, paused 112ms, total 113ms
D/UsbSettingsControl( 2564): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2564): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4575): Shutting down VM
D/dalvikvm( 4575): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+1ms, total 2ms
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{43988c38 stackId=1, 2 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43988c38 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3704): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4592 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3704): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3704): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4592): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4592): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4592): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/WebViewChromium( 4592): Binding Chromium to the background looper Looper (main, tid 1) {42f737f0}
I/chromium( 4592): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1946): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/BrowserProcessMain( 4592): Initializing chromium process, renderers=0
W/chromium( 4592): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4592): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4592): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4592): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4592): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4592): Remote Branch: 
I/Adreno-EGL( 4592): Local Patches: 
I/Adreno-EGL( 4592): Reconstruct Branch: 
I/dalvikvm( 4592): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4592): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4592): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4592): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4592): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4592): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4592): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4592): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4592): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4592): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4592): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4592): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4592): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4592): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4592): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4592): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4592): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4592): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4592): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4592): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4592): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4592): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4592): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4592): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4592): Enabling debug mode 0
,W/AwContents( 4592): nativeOnDraw failed; clearing to background color.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/InputMethodManagerService(  967): IME STATUS OFF
W/AwContents( 4592): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +380ms
,I/ActivityManager( 4592): Timeline: Activity_idle id: android.os.BinderProxy@42f74ed0 time:110556
,D/JsMessageQueue( 4592): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4592): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42f78fb0
,D/dalvikvm( 4592): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42f78fb0
,D/jxcore_app_log( 4592): JniHelper::setJavaVM(0x41f2a808), pthread_self() = 1633080680
,I/chromium( 4592): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3} time:110937
D/ActivityManager(  967): no-history finish of ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{43aad560 ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2564): [AUTORUN] onStop()
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/chromium( 4592): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4592): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/dalvikvm( 4592): GC_CONCURRENT freed 2681K, 12% free 21971K/24832K, paused 3ms+1ms, total 33ms
D/dalvikvm( 4592): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/dalvikvm( 4592): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 4592): GC_FOR_ALLOC freed 336K, 10% free 22356K/24832K, paused 27ms, total 28ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 24.046MB for 42652-byte allocation
D/dalvikvm( 4592): GC_FOR_ALLOC freed 104K, 11% free 22363K/24876K, paused 31ms, total 31ms
D/dalvikvm( 4592): GC_FOR_ALLOC freed 125K, 11% free 22383K/24876K, paused 24ms, total 24ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 24.124MB for 95956-byte allocation
D/dalvikvm( 4592): GC_FOR_ALLOC freed 178K, 11% free 22418K/24972K, paused 23ms, total 23ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 24.204MB for 143930-byte allocation
D/dalvikvm( 4592): GC_FOR_ALLOC freed 254K, 11% free 22465K/25116K, paused 23ms, total 23ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 24.318MB for 215890-byte allocation
D/dalvikvm( 4592): GC_FOR_ALLOC freed 366K, 12% free 22539K/25328K, paused 23ms, total 23ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 24.494MB for 323830-byte allocation
D/dalvikvm( 4592): GC_FOR_ALLOC freed 567K, 12% free 22659K/25648K, paused 24ms, total 24ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 24.765MB for 485740-byte allocation
,D/dalvikvm( 4592): GC_FOR_ALLOC freed 860K, 13% free 22836K/26124K, paused 24ms, total 24ms
,D/dalvikvm( 4592): GC_FOR_ALLOC freed 1122K, 12% free 23076K/26124K, paused 25ms, total 25ms
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/dalvikvm( 4592): GC_FOR_ALLOC freed 209K, 12% free 23040K/26124K, paused 25ms, total 26ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 25.716MB for 1092904-byte allocation
D/wpa_supplicant( 2027): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
,D/dalvikvm( 4592): GC_CONCURRENT freed 1802K, 14% free 23486K/27192K, paused 3ms+2ms, total 40ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
D/dalvikvm( 4592): GC_FOR_ALLOC freed 207K, 14% free 23394K/27192K, paused 28ms, total 28ms
I/dalvikvm-heap( 4592): Grow heap (frag case) to 26.583MB for 1639352-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4592): GC_CONCURRENT freed 1817K, 17% free 24002K/28796K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 4592): GC_FOR_ALLOC freed 1076K, 17% free 23991K/28796K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4592): Grow heap (frag case) to 27.947MB for 2459024-byte allocation
,D/dalvikvm( 4592): GC_CONCURRENT freed 1920K, 21% free 24737K/31200K, paused 1ms+3ms, total 31ms
,D/dalvikvm( 4592): GC_CONCURRENT freed 2480K, 20% free 25036K/31200K, paused 2ms+4ms, total 39ms
,D/dalvikvm( 4592): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 4592): GC_FOR_ALLOC freed 315K, 21% free 24806K/31200K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4592): Grow heap (frag case) to 29.916MB for 3688532-byte allocation
,D/dalvikvm( 4592): GC_CONCURRENT freed 2738K, 26% free 25948K/34804K, paused 1ms+3ms, total 37ms
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.466766 Y: -0.436584 Z: 9.796829 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466766 .y:-0.436584 .z:9.796829
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/dalvikvm( 4592): GC_FOR_ALLOC freed 1810K, 25% free 26128K/34804K, paused 27ms, total 27ms
W/jxcore-log( 4592): Initializing JXcore engine
W/jxcore-log( 4592): JXcore engine is ready
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.476181 Y: -0.431549 Z: 9.783508 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.476181 .y:-0.431549 .z:9.783508
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/dalvikvm( 4592): GC_CONCURRENT freed 400K, 17% free 28949K/34804K, paused 2ms+1ms, total 28ms
D/dalvikvm( 4592): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 4592): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/jxcore-log( 4592): Starting JXcore engine
W/jxcore-log( 4592): Platform android
W/jxcore-log( 4592): 
W/jxcore-log( 4592): Process ARCH arm
W/jxcore-log( 4592): 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/jxcore-log( 4592): JXcore Cordova bridge is ready!
I/jxcore-log( 4592): 
W/jxcore-log( 4592): JXcore engine is started
E/jxcore  ( 4592): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4592): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
I/chromium( 4592): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  967): Finishing activity token=Token{447645f8 ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  967): GC_FOR_ALLOC freed 1100K, 51% free 29579K/59892K, paused 70ms, total 70ms
,W/PluginManager( 4592): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 82ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43988c38 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1492): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1492): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1452): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1492): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1492): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1856): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 11:3:6
,I/[LGHome]EVENT( 1492): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,D/UpdateThreadPoolManager( 1856): 2 : This is isUpdating : false
,W/IInputConnectionWrapper( 4592): showStatusIcon on inactive InputConnection
I/InputMethodManagerService(  967): IME STATUS OFF
,D/WeatherQuickCover( 1856): 2 : quick cover state : opened : 0
D/WeatherService( 1856): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1856): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1856): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1856): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1856): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1856): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 11:3:6
D/WeatherService( 1856): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1856): 2 : quick cover state : opened : 0
D/Weather.Utils( 1856): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1856): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1856): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1856): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1856): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1856): 2 : This is isUpdating : false
D/WeatherService( 1856): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1856): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1856): 2 : Map key string is -2
D/lim     ( 1856): 2 : time = 11:03
I/WeatherReflect( 1856): Model Name : LG-D802
D/WeatherTheme( 1856): 2 : Different view - status_min_formatted : 01 != 03
D/WeatherTheme( 1856): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1856): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1856): 2 : Fixed theme : optimus
D/WeatherTheme( 1856): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1856): 2 : quick cover state : opened : 0
D/Weather.Utils( 1856): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1856): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1856): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1145): GC_FOR_ALLOC freed 5867K, 9% free 71585K/78564K, paused 32ms, total 32ms
,D/dalvikvm( 1492): GC_CONCURRENT freed 5425K, 9% free 60845K/66456K, paused 1ms+3ms, total 28ms
,D/dalvikvm( 1492): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1492): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1492): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1492): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1492): GC_FOR_ALLOC freed 5014K, 9% free 61984K/67844K, paused 18ms, total 18ms
,I/ActivityManager( 1492): Timeline: Activity_idle id: android.os.BinderProxy@42f78ff8 time:113863
,D/UsbSettings( 2564): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2564): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2564): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2564): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4383ab80 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1} time:113918
I/ActivityManager(  967): Killing 2106:android.process.media/u0a23 (adj 15): empty #17
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4592): call to OpenGL ES API with no current context (logged once per thread)
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{441aa288 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1}
,I/GAV2    ( 4532): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1554): onDestroy
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1492): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1492): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1492): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4100): [390] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4100): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1159): GC_CONCURRENT freed 2890K, 11% free 25444K/28512K, paused 7ms+1ms, total 59ms
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.454681 Y: -0.423615 Z: 9.790894 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454681 .y:-0.423615 .z:9.790894
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449768 Y: -0.426010 Z: 9.777039 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449768 .y:-0.426010 .z:9.777039
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2027): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8409 usec
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.462738 Y: -0.429230 Z: 9.802887 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462738 .y:-0.429230 .z:9.802887
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449936 Y: -0.417847 Z: 9.803833 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449936 .y:-0.417847 .z:9.803833
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  585): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.441620 Y: -0.417984 Z: 9.792465 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441620 .y:-0.417984 .z:9.792465
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.442856 Y: -0.428940 Z: 9.788574 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442856 .y:-0.428940 .z:9.788574
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449890 Y: -0.429886 Z: 9.791855 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449890 .y:-0.429886 .z:9.791855
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.453857 Y: -0.428223 Z: 9.799377 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453857 .y:-0.428223 .z:9.799377
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@442fc9f0)
,D/KeyguardViewMediator( 1145): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1145): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb87be450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.462921 Y: -0.431091 Z: 9.824722 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462921 .y:-0.431091 .z:9.824722
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/KeyguardViewMediator( 1145): handleNotifyScreenOn
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/KeyguardViewManager( 1145): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
I/WindowManager(  967): No lock screen! windowToken=null
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2027): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,D/wpa_supplicant( 2027): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2027): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2027): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=on
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1159): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{42f854c0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1159): enqueuing start. mLedList.size()=2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=3
,E/SlideAside( 3704): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1159): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1856): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 11:3:30
,I/SlideAside( 3704): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1856): 2 : This is isUpdating : false
,D/WeatherAncestor( 1856): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 11:3:30
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/WeatherService( 1856): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1856): 2 : shouldTimeTickRegistered : false
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1856): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1856): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1159): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1159): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1159): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1159): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 195, B = 195
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 411ms
,D/qdlights( 1159): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1159): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 183, B = 183
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1159): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 171, B = 171
D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370611230, nextTick: 28803, mDrawingTime: 0
,D/qdlights( 1159): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1159): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370611252, nextTick: 28781, mDrawingTime: 0
,D/qdlights( 1159): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 153, B = 153
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/qdlights( 1159): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 147, B = 147
D/WeatherService( 1856): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:3:31
,D/WeatherService( 1856): 2 : ACTION screen on
D/WeatherService( 1856): 2 : shouldTimeTickRegistered : false
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1856): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:3:31
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
,D/qdlights( 1159): set_light_notifications: 2,ff008d8d,10,0,2
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/GsmSST  ( 1452): Emergency Service
,D/qdlights( 1159): [Current] = 255, R = 0, G = 141, B = 141
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/qdlights( 1159): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 135, B = 135
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
D/KeyguardViewMediator( 1145): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1145): notifyScreenOffLocked
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1492): [Launcher.java:894:onPause()]onPause
D/qdlights( 1159): set_light_notifications: 2,ff008181,10,0,2
,V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1159): [Current] = 255, R = 0, G = 129, B = 129
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1159): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1159): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 117, B = 117
W/ProcessCpuTracker(  967): Skipping unknown process pid 4724
W/ProcessCpuTracker(  967): Skipping unknown process pid 4725
,W/ProcessCpuTracker(  967): Skipping unknown process pid 4733
D/KeyguardViewMediator( 1145): setting alarm to turn off keyguard, seq = 2, timeout = 5000
I/LGImmersionVibrator(  967): Vibrator off
D/qdlights( 1159): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 111, B = 111
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/[LGHome]EVENT( 1492): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  967): handleScreenStateChanged: false
D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 true
D/qdlights( 1159): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 105, B = 105
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4387e828 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  967): CMD_SCREEN_OFF 
,D/WifiController(  967): shouldWifiStayAwake TRUE
E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/qdlights( 1159): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 99, B = 99
D/KeyguardViewMediator( 1145): handleNotifyScreenOff
,D/KeyguardViewManager( 1145): onScreenTurnedOff()
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/BatteryObserver( 1159): usb Uevent not necessary.
D/VolumeVibrator( 1159): clear
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): handleMessage: X
D/qdlights( 1159): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 93, B = 93
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
,I/[LGHome]EVENT( 1492): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1159): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 87, B = 87
,D/WeatherService( 1856): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:3:31
,D/WeatherService( 1856): 2 : ACTION screen off
,D/WeatherService( 1856): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:3:31
V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/qdlights( 1159): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 81, B = 81
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1159): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 75, B = 75
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
,D/NfcService( 1477): NFC-C OFF
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
,D/qdlights( 1159): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 69, B = 69
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1159): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1159): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1159): set_light_notifications: 2,ff003333,10,0,2
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
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  585): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1145): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1145): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/KeyguardViewMediator( 1145): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1145): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370619538152299; DSPS: 4950744; Offset: 1453370468453435503
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370639539454113; DSPS: 5606147; Offset: 1453370468453425061
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370640037, nextTick: 59995, mDrawingTime: 0
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370640046, nextTick: 59984, mDrawingTime: 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Netstats( 1946): User is not opted-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1946): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1946): removeStateFiles() called
,D/PerfProfileCollectorService( 1946): User is not opt-in to Usage & Diagnostics.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370659540757335; DSPS: 6261549; Offset: 1453370468453446544
,W/ProcessCpuTracker(  967): Skipping unknown process pid 4837
,W/ProcessCpuTracker(  967): Skipping unknown process pid 4838
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370679541195140; DSPS: 6916924; Offset: 1453370468453426586
,D/wpa_supplicant( 2027): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370699541633986; DSPS: 7572298; Offset: 1453370468453438186
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370700041, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370700044, nextTick: 59988, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370719542942469; DSPS: 8227701; Offset: 1453370468453434413
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370739543776158; DSPS: 8883088; Offset: 1453370468453444127
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370759544640265; DSPS: 9538477; Offset: 1453370468453423224
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370760060, nextTick: 59972, mDrawingTime: 1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370760060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370779545063486; DSPS: 10193850; Offset: 1453370468453449717
,D/dalvikvm( 2637): GC_CONCURRENT freed 7810K, 33% free 16761K/24832K, paused 3ms+1ms, total 35ms
,D/dalvikvm( 2637): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  967): remove 43a82530
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370799545505979; DSPS: 10849225; Offset: 1453370468453434446
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x437bd720: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1554): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1554): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1554): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1554): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1554): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1554): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4100): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4100): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4100): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4100): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4100): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4100): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4100): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4100): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4100): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4100): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370819548471701; DSPS: 11504682; Offset: 1453370468453439963
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370820034, nextTick: 59996, mDrawingTime: 1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370820038, nextTick: 59994, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370839549934767; DSPS: 12160090; Offset: 1453370468453438185
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370859550763821; DSPS: 12815477; Offset: 1453370468453443265
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370879551210533; DSPS: 13470852; Offset: 1453370468453432213
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370880032, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370880046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370899552080108; DSPS: 14126240; Offset: 1453370468453447296
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370919552497860; DSPS: 14781614; Offset: 1453370468453437802
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370939553358946; DSPS: 15437002; Offset: 1453370468453444396
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370940044, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453370940055, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370959553781595; DSPS: 16092376; Offset: 1453370468453439799
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370979554775598; DSPS: 16747769; Offset: 1453370468453426722
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453370999555193455; DSPS: 17403142; Offset: 1453370468453447850
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371000039, nextTick: 59975, mDrawingTime: 9
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371000058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371019555632197; DSPS: 18058517; Offset: 1453370468453428828
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371039562953127; DSPS: 18714117; Offset: 1453370468453425540
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371059564237026; DSPS: 19369519; Offset: 1453370468453427700
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371060039, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371060057, nextTick: 59961, mDrawingTime: 5
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371079565083633; DSPS: 20024906; Offset: 1453370468453450333
,I/ActivityManager(  967): Killing 4190:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371099566564354; DSPS: 20680315; Offset: 1453370468453435692
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371119567434815; DSPS: 21335703; Offset: 1453370468453451661
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371120058, nextTick: 59971, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371120059, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371139567856318; DSPS: 21991077; Offset: 1453370468453445918
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371159568724748; DSPS: 22646466; Offset: 1453370468453429338
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371179569582552; DSPS: 23301854; Offset: 1453370468453432650
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371180056, nextTick: 59973, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371180058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371199571147077; DSPS: 23957265; Offset: 1453370468453440779
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371219572453892; DSPS: 24612668; Offset: 1453370468453435338
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371239573803467; DSPS: 25268072; Offset: 1453370468453442139
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371240053, nextTick: 59973, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371240058, nextTick: 59973, mDrawingTime: 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371259575154501; DSPS: 25923476; Offset: 1453370468453450400
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371279577139859; DSPS: 26578902; Offset: 1453370468453421598
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371299578486414; DSPS: 27234306; Offset: 1453370468453425379
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371300041, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371300054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371319579794374; DSPS: 27889708; Offset: 1453370468453451601
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371339581087284; DSPS: 28545111; Offset: 1453370468453432255
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371359582362432; DSPS: 29200513; Offset: 1453370468453425665
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371360029, nextTick: 59995, mDrawingTime: 5
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371360057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371379583965393; DSPS: 29855925; Offset: 1453370468453441712
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371399585251375; DSPS: 30511327; Offset: 1453370468453445956
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,I/EventLogService( 1946): Aggregate from 1453370500482 (log), 1453369165768 (data)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1554): Vacuum at: now=1453371403763 tag=VacuumService
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1554): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1554): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1554): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1554): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/ConfigService( 1554): onCreate
,I/ConfigFetchService( 1946): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1946): running network task: configservice_periodic
,E/WakeLock( 1946): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1946): launchTask
,I/ConfigFetchService( 1946): service connected
,D/ConfigFetchService( 1946): ConfigApi connection successful.
,D/dalvikvm( 1554): GC_CONCURRENT freed 1722K, 28% free 18033K/24832K, paused 4ms+4ms, total 46ms
,W/Uploader( 1554): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1554): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1554):  no longer exists, so no auth token.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,V/ConfigFetchTask( 1946): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VGN_BJ8eis6pBBXwGJTTawl9ytG-gpAztnXdvxQowZiS32AmiWDHuAJPs35ZEwtzeF_ly4QMQzIIp-fzVyVQOOKTW_D4ZUHU2pndsCzTPWmsCVRkTTjZ0Ry8AuKMeYlftRuZz30b1B-whnI1Crv9pOSj7RFvdjaShxs7O345H-DzwDwL-F-5PbJ4qpEVEad2_88FTg
,I/GoogleURLConnFactory( 1946): Using platform SSLCertificateSocketFactory
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/ConfigFetchTask( 1946): updating config table for com.google.android.gms
,I/ConfigFetchService( 1946): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1946): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1946): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1946): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1946): fetch service done; releasing wakelock
,I/ConfigFetchService( 1946): stopping self
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1554): onDestroy
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371419586778712; DSPS: 31166737; Offset: 1453370468453447414
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371420050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371420053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371439588194746; DSPS: 31822144; Offset: 1453370468453429121
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371459589510832; DSPS: 32477547; Offset: 1453370468453432952
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371479590832022; DSPS: 33132950; Offset: 1453370468453441886
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371480038, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371480044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371499592111546; DSPS: 33788352; Offset: 1453370468453439671
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371519593485183; DSPS: 34443757; Offset: 1453370468453440017
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371539594767207; DSPS: 35099159; Offset: 1453370468453440303
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371540060, nextTick: 59970, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371540061, nextTick: 59972, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_CONCURRENT freed 2165K, 49% free 30571K/59892K, paused 6ms+8ms, total 160ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371559596783711; DSPS: 35754585; Offset: 1453370468453442647
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371579598133545; DSPS: 36409989; Offset: 1453370468453449708
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371599599441612; DSPS: 37065392; Offset: 1453370468453445519
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371600038, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371600043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371619600732333; DSPS: 37720795; Offset: 1453370468453423984
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371639602035659; DSPS: 38376197; Offset: 1453370468453445572
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
,D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  967): handleMessage: E msg.what=147460,
D/WifiStateMachine(  967): processMsg: ConnectedState,
D/WifiStateMachine(  967): processMsg: L2ConnectedState,
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost,
,D/WifiStateMachine(  967): Stopping DHCP and clearing IP
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  967): doBoolean: SET ps 1,
,D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8368d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2027):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2027): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2027): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2027): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/wpa_supplicant( 2027): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
,D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
D/wpa_supplicant( 2027): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2027): wlan0: nl80211: scan request
,D/wpa_supplicant( 2027): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/DhcpStateMachine(  967): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2027): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2027): wlan0: nl80211: Scan trigger
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.155/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
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
D/QCNEA   (  604): |CAC| dispatchNetCfg: updating:0xb87498dc
,D/QCNEA   (  604): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/WifiHS20(  967): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 0
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5784 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
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
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
,V/        (  264): RouteController
V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
,D/HyLog   ( 5784): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5784): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5784): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 5784): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5784): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5784): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
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
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x628eb330 clazz=0x83e00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
V/NativeCrypto( 1554): Read error: ssl=0x63a4a5c8: I/O error during system call, Connection timed out
V/NativeCrypto( 1554): SSL shutdown failed: ssl=0x63a4a5c8: I/O error during system call, Broken pipe
I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5827 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  967): Killing 3304:com.android.mms/u0a35 (adj 15): empty #17
D/CountryDetector(  967): No listener is left
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5827): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5827): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  967): StoppedState
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 5827): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/Batterystats( 1946): User is not opted-in to Usage & Diagnostics.
,D/QRemote ( 5827): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 5827): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5827): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 5827): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5827): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5827): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5827): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5827): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 4222:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/wpa_supplicant( 2027): nl80211: Event message available
D/wpa_supplicant( 2027): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2027): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2027): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2027): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 2027): nl80211: Survey data missing
D/wpa_supplicant( 2027): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 3 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 4 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 5 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 2027): wlan0: New scan results available
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2027): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2027): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2027): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2027): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2027): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2027): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2027): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2027): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-83
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: 4: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-90 wps
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2027): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2027): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
,D/wpa_supplicant( 2027): wlan0: Selecting BSS from priority group 1,
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 2027): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2027): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2027): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps,
D/wpa_supplicant( 2027): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2027): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700',
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0,
,D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2027): wlan0: [MDM] lg mdm allow/disallow auto connect is not set ,
,D/wpa_supplicant( 2027): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb836a5a8  current_ssid=0x0
,D/wpa_supplicant( 2027): scard is not null..,
,D/wpa_supplicant( 2027): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
,D/wpa_supplicant( 2027): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2027): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30,
,D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
,D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00,
,D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00,
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2027): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2027): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2027): wlan0: Cancelling scan request
D/wpa_supplicant( 2027): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2027): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2027): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2027): RSN: PMKSA cache search - network_ctx=0xb836a5a8 try_opportunistic=0
D/wpa_supplicant( 2027): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2027): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2027): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2027): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2027): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2027): wlan0: WPA: using PTK CCMP
,D/wpa_supplicant( 2027): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2027): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2027): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2027): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2027): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 2027): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2027): nl80211: Unsubscribe mgmt frames handle 0xb8369590 (mode change)
D/wpa_supplicant( 2027): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0c
,D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0d
,D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590,
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2027): nl80211: Register frame type=0xd0 nl_handle=0xb8369590,
D/wpa_supplicant( 2027): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2027): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2027):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027):   * freq=2412,
D/wpa_supplicant( 2027):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2027):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027):   * Auth Type 0
D/wpa_supplicant( 2027):   * WPA Versions 0x2
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 38:f8:89:11:e9:11]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81],
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:97]
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
D/wpa_supplicant( 2027): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState,
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 2027): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  967): MasterInitialState.processMessage what=3
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
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
D/wpa_supplicant( 2027): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
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
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
,D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2027): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 3a 05 59 54 44 a9 e2 14 d2 46 dd cf 15 04 88 ...
D/wpa_supplicant( 2027): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2027): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2027): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2027): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2027): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2027):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2027):   key_nonce - hexdump(len=32): 3a 05 59 54 44 a9 e2 14 d2 46 dd cf 15 04 88 6d 7d 14 ba 05 52 63 cd dd ba 43 65 cc e3 7a 76 94
D/wpa_supplicant( 2027):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 3a 05 59 54 44 a9 e2 14 d2 46 dd cf 15 04 88 ...
D/wpa_supplicant( 2027): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2027): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2027): Get randomness: len=32 entropy=6
,D/wpa_supplicant( 2027): WPA: Renewed SNonce - hexdump(len=32): ac 91 69 a8 84 1f 6d c3 1f 65 54 1b d8 d3 c7 09 10 e5 8c f1 d4 51 e7 4d db c0 26 3d 4b f3 99 33
D/wpa_supplicant( 2027): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2027): WPA: Nonce1 - hexdump(len=32): ac 91 69 a8 84 1f 6d c3 1f 65 54 1b d8 d3 c7 09 10 e5 8c f1 d4 51 e7 4d db c0 26 3d 4b f3 99 33
D/wpa_supplicant( 2027): WPA: Nonce2 - hexdump(len=32): 3a 05 59 54 44 a9 e2 14 d2 46 dd cf 15 04 88 6d 7d 14 ba 05 52 63 cd dd ba 43 65 cc e3 7a 76 94
D/wpa_supplicant( 2027): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2027): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2027): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2027): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2027): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2027): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): WPA: Derived Key MIC - hexdump(len=16): ff fc e4 14 da 9d 12 04 1f dd 7d 92 cd 2f 32 8d
D/wpa_supplicant( 2027): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 ac 91 69 a8 84 1f 6d c3 1f 65 54 1b d8 d3 c7 ...,
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2027): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2027): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 3a 05 59 54 44 a9 e2 14 d2 46 dd cf 15 04 88 ...
D/wpa_supplicant( 2027): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2027): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2027): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2027): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2027):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2027):   key_nonce - hexdump(len=32): 3a 05 59 54 44 a9 e2 14 d2 46 dd cf 15 04 88 6d 7d 14 ba 05 52 63 cd dd ba 43 65 cc e3 7a 76 94
D/wpa_supplicant( 2027):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_rsc - hexdump(len=8): 1d ed 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2027):   key_mic - hexdump(len=16): 13 ad 10 c4 1d ef 51 7b 68 81 18 1f e4 5a 1f 4e
D/wpa_supplicant( 2027): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 3a 05 59 54 44 a9 e2 14 d2 46 dd cf 15 04 88 ...
D/wpa_supplicant( 2027): RSN: encrypted key data - hexdump(len=56): 5d 0f a5 0c 26 57 c6 69 59 cf c4 35 63 4b 2c 21 20 d8 bf e0 46 81 33 27 29 ae 5e f6 e5 a0 09 cf ...
D/wpa_supplicant( 2027): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2027): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2027): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2027): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 2a 0b ...
D/wpa_supplicant( 2027): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2027): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2027): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2027): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): WPA: Derived Key MIC - hexdump(len=16): 30 68 63 96 6e b7 ae c9 7b 78 26 f9 ec 1c e6 ae
D/wpa_supplicant( 2027): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2027): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8369c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2027):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2027): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2027): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2027): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2027): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2027): WPA: RSC - hexdump(len=6): 1d ed 00 00 00 00
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f7303a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2027):    broadcast key
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/wpa_supplicant( 2027): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2027): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2027): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2027): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2027): netlink: Operstate: linkmode=-1, operstate=6
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
D/wpa_supplicant( 2027): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2027): EAPOL authentication completed successfully
D/wpa_supplicant( 2027): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2027): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2027): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): Network connection established
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2027): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2027): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
,I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
,D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
,D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-37ms what=147462 obj=android.net.wifi.StateChangeResult@441fc180 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-33ms what=147462 obj=android.net.wifi.StateChangeResult@43a92020 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-35ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/DhcpStateMachine(  967): StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] connect :false
I/AppUp4:CustModeStarterReceiver( 4209): onReceive
D/AppUp4:CustFacade( 4209): Context : android.app.ReceiverRestrictedContext@42f8de20
D/AppUp4:CustFacade( 4209): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4209): isOpenOperator : true
D/AppUp4:CustFacade( 4209): isPhone : true
I/LicenseContentProvider( 4258): start selecting data
D/SIMObserver( 4258): simInfo1
I/AppUp4:EulaManager( 4209): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4209): begin check event
I/AppUp4:CustModeStarterReceiver( 4209): Event For GoodConnectivity, noConnectivity : true, but skip! 
,I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5868 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5868): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5868): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET ps 0
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  967):    returned null
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  264): Setting iface cfg
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@439aadc8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@439aadc8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): addressUpdated: 192.168.1.155/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.155/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2027): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2027): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2027): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2027): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2027): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2027): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): DHCP successful
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
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
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
,E/Parcel  (  604): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
,D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine(  967): handleMessage: X
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  604): Reading a NULL string not supported here.
D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
E/Parcel  (  604): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,V/DownloadManager( 5868): DownloadService onCreate
,I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/DownloadManager( 5868): in removeSpuriousFiles
,D/EAS     ( 4514): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4514): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/        (  264): RouteController
,V/DownloadManager( 5868): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fb9dc8 on behalf of 5868
,D/eas_req ( 4514): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 5868): in trimDatabase
,V/        (  264): RouteController
,V/DownloadManager( 5868): DownloadService onStartCommand
,V/DownloadManager( 5868): DownloadService onStartCommand
,V/DownloadManager( 5868): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5868): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/        (  264): RouteController
V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fbd388 on behalf of 5868
,V/        (  264): RouteController
,V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fbe840 on behalf of 5868
,I/ActivityManager(  967): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=5903 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
V/        (  264): RouteController
W/linker  ( 4514): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4514): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4514): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4514): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4514): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
V/DownloadManager( 5868): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/HtmlEditor( 4514): register_HtmlEditor, Success
D/HtmlEditor( 4514): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4514): register_HtmlEditorTimer, Success
D/HtmlEditor( 4514): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4514): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4514): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4514): register_HtmlEditorFont, Success
D/HtmlEditor( 4514): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4514): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4514): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
V/        (  264): RouteController
V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fc2a08 on behalf of 5868
D/HtmlEditor( 4514): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4514): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4514): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4514): JNI_OnLoad Success
I/HubEmail( 4514): JNI_OnLoad()
I/HubEmail( 4514): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4514): registerNatives()
I/HubEmail( 4514): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4514): registerNativeMethods()
I/HubEmail( 4514): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
V/        (  264): RouteController
V/DownloadManager( 5868): DownloadService onDestroy
V/        (  264): RouteController
W/Settings( 4514): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 5903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5903): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5903): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
,I/ActivityManager(  967): Killing 4438:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/QCNEA   (  604): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  604): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  604): |CAC| updateNetCfgInfo
V/QCNEA   (  604): |CAC| *********************************************
V/QCNEA   (  604): |CAC|                   Netconfig               
V/QCNEA   (  604): |CAC| *********************************************
V/QCNEA   (  604): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  604): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  604): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  604): |CAC| 	NetConfig: ip4        =192.168.1.155
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
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
D/QCNEA   (  604): |CAC| dispatchNetCfg: updating:0xb87498dc
D/QCNEA   (  604): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ConversationSkinProvider( 5903): skin provider oncreate
,E/[MMS]   ( 5903): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 5903): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5903): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5903): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5903): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
,E/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 5903): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 5903): MmsSettings: Matching Xml Data file name = 2131034168
,D/[MMS]   ( 5903): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 5903): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
,E/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 5903): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_dr_r = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_validity = [6]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 5903): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 5903): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_limit = [50]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 5903): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   anonymous_spam_setting = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 5903): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   discard_visible = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   inline_msg_item = [1]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 5903): MmsSettings: [LGE]   two_finger_flick = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   docomo_led_button_blink = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 5903): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 5903): MmsSettings: [LGE]   appointment_invisible = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   save_to_draft = [0]
,D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   mms_callback = [0]
D/[MMS]   ( 5903): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 5903): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 5903): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,I/[MMS]   ( 5903): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 5903): _DRM_ServiceGet() : Bind lgdrm service
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b8b84af8
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
,E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
,E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
,E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b8b84b10
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
,E/Diag_Lib(  276): Setting the api flag to : 1
,E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
,E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 5903): isDrmV1 =true
,V/DrmWrapper( 5903): isDrmV2 =false
,V/MmsConfig( 5903): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 5903): [setMmsEnabledWhenDataDisabled]enabled=true
,V/MmsConfigStaticVar( 5903): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 5903): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 5903): Contact init()_Create new insatnce
,I/MessagingNotification( 5903): registerLEDObserver
,I/MessagingNotification( 5903): registerLEDObserver REGISTER
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/CountryDetector(  967): The first listener is added
,V/MmsConfig( 5903): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
,D/LocationManagerService(  967): getProviders()=[passive, gps]
,D/LocationManagerService(  967): request 44c6ff68 passive Request[POWER_NONE passive fastest=0] from android(1000)
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,I/LOG_TAG ( 5903): registerContactDBChangeObserver
,I/LgeMiscReceiver( 5903): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 5903): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 5903): networkInfo.isConnected() = false
E/ActivityThread( 5903): Failed to find provider info for com.lge.ims.provider.uc
,V/LGRssiData( 5903): [loadRssi] File not exist 
,V/LGRssiData( 5903): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5903): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5903): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5903): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5903): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5947 uid=10052 gids={50052, 3003}
I/ActivityManager(  967): Killing 4473:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5947): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5947): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5947): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5947): [loadRssi] File not exist 
,V/LGRssiData( 5947): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5947): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 5947): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5947): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 5947): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,W/BaseRuntimeLoader( 5947): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5947): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 5947): onReceive CONNECTIVITY_CHANGE networkType=1
,V/TelephonyAutoProfiling( 5947): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5947): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5947): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5966 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 5947): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5947): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  967): Killing 4501:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1946): Checking schedule, now: 1453371655431 next: 1453370533222
,I/CheckinService( 1946): active receiver: enabled
D/HyLog   ( 5966): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5966): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5966): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1946): Preparing to send checkin request
,I/EventLogService( 1946): Accumulating logs since 1453371403714
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5980 uid=10066 gids={50066, 4002, 3003, 1028}
,E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 5980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5980): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  967): Killing 4271:com.android.contacts/u0a21 (adj 15): empty #17
I/LGDMClient( 2836): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5993 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,E/LGDMClient( 2836): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2836): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2836): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2836): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 5993): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5993): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5993): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5993): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6011 uid=10101 gids={50101, 1028, 1015, 3003}
D/wpa_supplicant( 2027): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2027): EAPOL: disable timer tick
I/ActivityManager(  967): Killing 4285:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6011): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6011): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6011): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 6011): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Wireless_Storage( 6011): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6011): intf.getDisplayName() = lo
I/Wireless_Storage( 6011): intf.getDisplayName() = sit0
I/Wireless_Storage( 6011): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6011): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6011): intf.getDisplayName() = wlan0
D/NFS     ( 6011): interface name:wlan0 name:wlan0
D/NFS     ( 6011): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6011): interface name:wlan0 name:wlan0
,D/NFS     ( 6011): addr:192.168.1.155 broadcast:192.168.1.255
,I/Wireless_Storage( 6011): CONNECT : WIFI_CONNECT
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6025 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4532:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+3ms, total 32ms
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6025): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6025): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6025): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 26ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
,W/GAV2    ( 6025): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm(  967): GC_EXPLICIT freed 1511K, 49% free 30557K/59508K, paused 4ms+12ms, total 179ms
,W/CheckinRequestBuilder( 1946): awaiting user notification for token
D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x439a79d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.155/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  967): handleMessage: X
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,V/WebViewChromium( 6025): Binding Chromium to the main looper Looper (main, tid 1) {42f7e2e8}
,I/chromium( 6025): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6025): Initializing chromium process, renderers=0
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6049 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,W/chromium( 6025): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6025): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6025): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6025): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6025): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6025): Remote Branch: 
I/Adreno-EGL( 6025): Local Patches: 
I/Adreno-EGL( 6025): Reconstruct Branch: 
,D/HyLog   ( 6049): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6049): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6049): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6049): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6049): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6049): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6049): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6049): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6049): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6049): install
,I/NSApplication( 6025): Starting up...
,I/MultiDex( 6049): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6049): loading existing secondary dex files
,I/MultiDex( 6049): load found 3 secondary dex files
,I/MultiDex( 6049): install done
I/ActivityManager(  967): Killing 1838:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,D/dalvikvm( 6049): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 6049): VFY: unable to resolve instance field 61
,D/dalvikvm( 6049): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6049): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6049): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6049): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 6049): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6049): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6049): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6049): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6049): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6049): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7a428
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm( 6049): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7a428
D/dalvikvm( 6049): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7a428, skipping init
D/dalvikvm( 6049): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f7a428
D/dalvikvm( 6049): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f7a428
V/JNIHelp ( 6049): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/QRemote ( 5827): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5827): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5827): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5827): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5827): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5827): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5784): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5784): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5827): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5827): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5827): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5827): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/dalvikvm( 6049): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7a428
,D/dalvikvm( 6049): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42f7a428
D/dalvikvm( 6049): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f7a428
,D/dalvikvm( 6049): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42f7a428
,I/ProviderInstaller( 6049): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1946): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 6049): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 6049): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x000d
I/ActivityManager(  967): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6079 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/dalvikvm( 6049): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 6049): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1946): Restart initialization of location
,D/HyLog   ( 6079): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6079): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6079): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6079): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6079): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6079): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6079): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6079): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6079): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6079): install
,I/MultiDex( 6079): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6079): loading existing secondary dex files
,I/MultiDex( 6079): load found 3 secondary dex files
,I/MultiDex( 6079): install done
,D/dalvikvm( 6079): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6079): VFY: unable to resolve instance field 61
,D/dalvikvm( 6079): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 6079): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6079): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6079): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 6079): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6079): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6079): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6079): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6079): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6079): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7b548
D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/dalvikvm( 6079): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7b548
,D/dalvikvm( 6079): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7b548, skipping init
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d99000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d99000
,D/dalvikvm( 6079): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f7b548
,D/dalvikvm( 6079): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f7b548
,V/JNIHelp ( 6079): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
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
,I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=630699667
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6079): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42f7b548
D/dalvikvm( 6079): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42f7b548
,D/dalvikvm( 6079): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42f7b548
,D/dalvikvm( 6079): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42f7b548
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ProviderInstaller( 6079): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1554): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1554): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1946): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/dalvikvm( 6049): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4312bd78
,D/dalvikvm( 6049): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4312bd78
,D/dalvikvm( 6049): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4312bd78, skipping init
,D/LocationInitializer( 1946): Restart initialization of location
,I/dalvikvm( 6079): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 6079): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 6079): VFY: replacing opcode 0x6e at 0x003f
,D/WearableService( 6079): callingUid 10006, callindPid: 6079
,E/dalvikvm( 6079): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
,W/dalvikvm( 6079): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 6079): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 6079): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,I/dalvikvm( 6079): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6079): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6079): VFY: replacing opcode 0x6e at 0x000d
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
I/dalvikvm( 6079): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6079): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6079): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1427): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1427): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 6049): Total arena pages for JIT: 11
,I/dalvikvm( 6049): Total arena pages for JIT: 12
I/dalvikvm( 6049): Total arena pages for JIT: 13
,I/dalvikvm( 6049): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6049): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6102): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6049): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6049): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 105ms
,I/Adreno-EGL( 6049): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6049): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6049): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6049): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6049): Remote Branch: 
I/Adreno-EGL( 6049): Local Patches: 
I/Adreno-EGL( 6049): Reconstruct Branch: 
,W/Settings( 6049): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 6049): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6049): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6049): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6049): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6049): Remote Branch: 
I/Adreno-EGL( 6049): Local Patches: 
I/Adreno-EGL( 6049): Reconstruct Branch: 
,I/Adreno-EGL( 6049): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6049): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6049): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6049): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6049): Remote Branch: 
I/Adreno-EGL( 6049): Local Patches: 
I/Adreno-EGL( 6049): Reconstruct Branch: 
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=2325579419
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4209): onReceive
,D/AppUp4:CustFacade( 4209): Context : android.app.ReceiverRestrictedContext@42f8de20
D/AppUp4:CustFacade( 4209): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4209): isOpenOperator : true
D/AppUp4:CustFacade( 4209): isPhone : true
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/LicenseContentProvider( 4258): start selecting data
,D/SIMObserver( 4258): simInfo1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/AppUp4:EulaManager( 4209): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4209): begin check event
I/AppUp4:CustModeStarterReceiver( 4209): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4209): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4209): call method handleAsyncCustNotification.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/AppUp4:CustModeStarterReceiver( 4209): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4209): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4209): handleAsyncCustNotification do not startCustService
V/DownloadManager( 5868): DownloadService onCreate
I/DownloadManager( 5868): in removeSpuriousFiles
V/DownloadManager( 5868): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4514): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fc6d58 on behalf of 5868
D/EAS     ( 4514): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4514): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 5868): in trimDatabase
V/DownloadManager( 5868): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fc8328 on behalf of 5868
I/LgeMiscReceiver( 5903): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 5903): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 5903): networkInfo.isConnected() = false
,W/Settings( 4514): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 5868): DownloadService onStartCommand
,D/MobileConnectivityChangeReceiver( 5947): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 5868): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 5947): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fca900 on behalf of 5868
,V/DownloadManager( 5868): DownloadService onDestroy
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5993): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2836): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 5993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 6011): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6011): CONNECT : WIFI_CONNECT
E/LGDMClient( 2836): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2836): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2836): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2836): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 1946): GC_CONCURRENT freed 1850K, 22% free 19535K/24832K, paused 4ms+14ms, total 79ms
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4209): onReceive
,D/AppUp4:CustFacade( 4209): Context : android.app.ReceiverRestrictedContext@42f8de20
D/AppUp4:CustFacade( 4209): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4209): isOpenOperator : true
,D/AppUp4:CustFacade( 4209): isPhone : true
,I/LicenseContentProvider( 4258): start selecting data
,D/SIMObserver( 4258): simInfo1
,I/AppUp4:EulaManager( 4209): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4209): begin check event
,I/AppUp4:CustModeStarterReceiver( 4209): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5868): DownloadService onCreate
,I/DownloadManager( 5868): in removeSpuriousFiles
D/EAS     ( 4514): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5868): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4514): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fcf350 on behalf of 5868
V/DownloadManager( 5868): DownloadService onStartCommand
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,V/DownloadManager( 5868): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 5868): in trimDatabase
,V/DownloadManager( 5868): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fd2248 on behalf of 5868
,V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fd1680 on behalf of 5868
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,W/Settings( 4514): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 5903): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 5903): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 5868): DownloadService onDestroy
I/LgeMiscReceiver( 5903): networkInfo.isConnected() = true
,D/PhoneState( 5903): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5947): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5947): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5993): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2836): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 6011): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6011): CONNECT : WIFI_CONNECT
,W/ContextImpl( 5993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2836): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2836): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2836): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2836): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1946): Sending checkin request (12357 bytes)
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.155
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  967): RunningState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4209): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4209): onReceive
,D/AppUp4:CustFacade( 4209): Context : android.app.ReceiverRestrictedContext@42f8de20
,D/AppUp4:CustFacade( 4209): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4209): isOpenOperator : true
,D/AppUp4:CustFacade( 4209): isPhone : true
,I/LicenseContentProvider( 4258): start selecting data
,D/SIMObserver( 4258): simInfo1
,I/AppUp4:EulaManager( 4209): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4209): begin check event
,I/AppUp4:CustModeStarterReceiver( 4209): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4514): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5868): DownloadService onCreate
,D/EAS     ( 4514): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 5903): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 5903): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 5903): networkInfo.isConnected() = true
,D/PhoneState( 5903): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5947): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5947): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2836): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5993): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6011): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6011): CONNECT : WIFI_CONNECT
,I/DownloadManager( 5868): in removeSpuriousFiles
,V/DownloadManager( 5868): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 4514): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2836): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fd6878 on behalf of 5868
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 5868): in trimDatabase
V/DownloadManager( 5868): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 2836): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 5868): DownloadService onStartCommand
V/DownloadManager( 5868): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fd86e8 on behalf of 5868
V/DownloadManager( 5868): created cursor android.database.sqlite.SQLiteCursor@42fda330 on behalf of 5868
,E/LGDMClient( 2836): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2836): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,V/DownloadManager( 5868): DownloadService onDestroy
,D/LGDMClient( 2836): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2836): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371659603606276; DSPS: 39031609; Offset: 1453370468453429275
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371660047, nextTick: 59983, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371660048, nextTick: 59985, mDrawingTime: 0
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x4430b068: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1946): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,I/CheckinTask( 1946): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1946): Checking schedule, now: 1453371660315 next: 1453949056308
,I/CheckinService( 1946): active receiver: disabled
,I/CheckinService( 1946): Checking schedule, now: 1453371660358 next: 1453949056308
,I/CheckinService( 1946): active receiver: disabled
,D/GCM     ( 1554): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1554): Connected
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1554): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GAV2    ( 6025): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  967): Killing 5784:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): Killing 4100:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): Killing 5827:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1492): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
,I/[LGHome]Launcher( 1492): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,E/SlideAside( 3704): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3704): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6227 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6227): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
,D/HyLog   ( 6227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6227): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6227): MmsConfig.loadMmsSettings
I/Babel   ( 6227): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6227): MmsConfig.loadFromDatabase
,I/MediaCodecList( 6227): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 6227): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 6227): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6227): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 6227): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6227): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6227): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6227): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6227): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6227): MmsConfig.loadFromResources
,E/Babel   ( 6227): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6227): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 6227): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/[LGHome]EVENT( 1492): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/LGRssiData( 6227): [loadRssi] File not exist 
V/LGRssiData( 6227): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6227): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6227): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6227): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6227): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/GmsNetworkLocationProvi( 1427): DISABLE
,D/AppUp4:Utils( 4209): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4209): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4209): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppUp4:CustModeStarterReceiver( 4209): onReceive
,D/AppUp4:CustFacade( 4209): Context : android.app.ReceiverRestrictedContext@42f8de20
D/AppUp4:CustFacade( 4209): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4209): isOpenOperator : true
,D/AppUp4:CustFacade( 4209): isPhone : true
,I/LicenseContentProvider( 4258): start selecting data
,D/SIMObserver( 4258): simInfo1
,I/AppUp4:EulaManager( 4209): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4209): begin check event
D/AppUp4:Utils( 4209): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4209): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6273 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,D/dalvikvm(  967): GC_EXPLICIT freed 2979K, 49% free 30703K/59508K, paused 4ms+15ms, total 166ms
,I/ActivityManager(  967): Killing 5868:android.process.media/u0a23 (adj 15): empty #17
,D/HyLog   ( 6273): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6273): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6273): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 6273): BUILD Country: EU
,I/SystemConfig( 6273): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4514:com.lge.email/u0a24 (adj 15): empty #17
,I/SystemConfig( 6273): systemFeature RCS result false
,D/SystemConfig( 6273): refreshRcsSupport() :false
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6290 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6290): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6290): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6290): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  967): Killing 5903:com.android.mms/u0a35 (adj 15): empty #17
I/IcingCorporaProvider( 2649): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/LocationManagerService(  967): remove 44c6ff68
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
D/CountryDetector(  967): No listener is left
I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6309 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6309): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6309): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 6309): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6309): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6309): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6309): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 6309): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6309): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6309): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6309): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6309): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6309): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6309): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6309): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6309): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/IcingCorporaProvider( 2649): UpdateCorporaTask done [took 260 ms] updated apps [took 259 ms] 
,I/dalvikvm( 6309): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6309): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6309): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6309): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6309): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6309): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6309): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6309): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6309): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 6309): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 6309): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6309): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  967): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6344 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6344): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6344): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6344): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6309): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 6309): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6309): VFY: replacing opcode 0x6e at 0x0049
,D/dalvikvm( 1554): GC_EXPLICIT freed 1299K, 28% free 18056K/24832K, paused 3ms+7ms, total 57ms
,D/Finsky  ( 6309): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/DownloadManager( 6344): DownloadService onCreate
,D/Finsky  ( 6309): [1] 2.run: Finished loading 1 libraries.
,I/DownloadManager( 6344): in removeSpuriousFiles
,V/DownloadManager( 6344): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/PackageBroadcastService( 1946): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
V/DownloadManager( 6344): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6344): DownloadService onStartCommand
,V/DownloadManager( 6344): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/PackageBroadcastService( 1946): Null package name or gms related package.  Ignoreing.
,V/DownloadManager( 6344): created cursor android.database.sqlite.SQLiteCursor@42fbf0b0 on behalf of 6344
,V/DownloadManager( 6344): created cursor android.database.sqlite.SQLiteCursor@42fc1638 on behalf of 6309
,V/DownloadManager( 6344): created cursor android.database.sqlite.SQLiteCursor@42fc3228 on behalf of 6344
,I/DownloadManager( 6344): in trimDatabase
,V/DownloadManager( 6344): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/Icing   ( 1946): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6344): created cursor android.database.sqlite.SQLiteCursor@42fc5518 on behalf of 6344
,V/DownloadManager( 6344): DownloadService onDestroy
,I/ActivityManager(  967): Killing 5947:com.google.android.setupwizard/u0a52 (adj 15): empty #17
D/Finsky  ( 6309): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 6309): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6309): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6309): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6309): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6309): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6309): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,W/Finsky  ( 6309): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.78/generate_204
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/dalvikvm( 6309): Total arena pages for JIT: 11
,I/dalvikvm( 6309): Total arena pages for JIT: 12
I/dalvikvm( 6309): Total arena pages for JIT: 13
,I/dalvikvm( 6309): Total arena pages for JIT: 14
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1554): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1554): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1554): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1554): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1554): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1554): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6309): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6309): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6309): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6309): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DeviceConnectionService( 1427): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6227): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  967): Killing 5966:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43388738 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371679604999550; DSPS: 39687014; Offset: 1453370468453449258
,D/Finsky  ( 6309): [474] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6309): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371699606981729; DSPS: 40342439; Offset: 1453370468453447794
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371719608565160; DSPS: 40997851; Offset: 1453370468453444311
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371720048, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371720054, nextTick: 59978, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371739609858328; DSPS: 41653254; Offset: 1453370468453425223
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371759611146603; DSPS: 42308656; Offset: 1453370468453431760
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1453371779612660137; DSPS: 42964065; Offset: 1453370468453449932
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371780051, nextTick: 59978, mDrawingTime: 2
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1453371780054, nextTick: 59978, mDrawingTime: 0
,TIME-OUT KILL (timeout was 1200000ms)
```
