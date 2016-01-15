#### Test 561517803567b2a_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 1526): GC_EXPLICIT freed 828K, 29% free 17873K/24832K, paused 2ms+7ms, total 31ms
W/BaseAppContext( 1856): Using Auth Proxy for data requests.
W/BaseAppContext( 1856): Using Auth Proxy for data requests.
W/BaseAppContext( 1856): Using Auth Proxy for data requests.
W/BaseAppContext( 1856): Using Auth Proxy for data requests.
W/GAV2    ( 4743): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 4157:com.google.android.configupdater/u0a3 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433cdc00 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2}
,D/dalvikvm( 1856): GC_CONCURRENT freed 1530K, 22% free 19561K/24832K, paused 3ms+10ms, total 50ms
D/ChimeraCfgMgr( 1856): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1856): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4798): 
D/AndroidRuntime( 4798): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4798): CheckJNI is OFF
D/dalvikvm( 4798): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4798): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4798): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4798): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4798): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/ConfigFetchService( 1856): fetch service done; releasing wakelock
I/ConfigFetchService( 1856): stopping self
D/dalvikvm( 4798): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1856): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1856): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4798): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4798): failed to load memtrack module: -2
I/Icing   ( 1856): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4798): Calling main entry com.android.commands.am.Am
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4798
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433cdc00 stackId=1, 2 tasks}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (116 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  966): GC_FOR_ALLOC freed 23986K, 52% free 28853K/59744K, paused 113ms, total 113ms
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  966): startService SlideAside
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{433cdc00 stackId=1, 2 tasks}
D/UsbSettingsControl( 2638): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2638): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433cdc00 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 4038): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/AndroidRuntime( 4798): Shutting down VM
D/dalvikvm( 4798): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4818 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 4038): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4038): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4818): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4818): Binding Chromium to the background looper Looper (main, tid 1) {428cd2f0}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/chromium( 4818): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4818): Initializing chromium process, renderers=0
W/chromium( 4818): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4818): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4818): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4818): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4818): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4818): Remote Branch: 
I/Adreno-EGL( 4818): Local Patches: 
I/Adreno-EGL( 4818): Reconstruct Branch: 
I/dalvikvm( 4818): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4818): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4818): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4818): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4818): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4818): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4818): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4818): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4818): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4818): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4818): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4818): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4818): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4818): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4818): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4818): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4818): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4818): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4818): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4818): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4818): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4818): Enabling debug mode 0
W/AwContents( 4818): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  966): IME STATUS OFF
W/AwContents( 4818): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +460ms
I/ActivityManager( 4818): Timeline: Activity_idle id: android.os.BinderProxy@428ceac0 time:111169
D/JsMessageQueue( 4818): Set native->JS mode to OnlineEventsBridgeMode
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.439774 Y: -0.400986 Z: 9.806015 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.439774 .y:-0.400986 .z:9.806015
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/dalvikvm( 4818): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428d4d00
D/dalvikvm( 4818): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428d4d00
D/jxcore_app_log( 4818): JniHelper::setJavaVM(0x41798838), pthread_self() = 1640063056
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.452240 Y: -0.420319 Z: 9.812408 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452240 .y:-0.420319 .z:9.812408
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
I/chromium( 4818): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3} time:111457
D/ActivityManager(  966): no-history finish of ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{43157d48 ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2 f}
D/UsbSettings( 2638): [AUTORUN] onStop()
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/chromium( 4818): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4818): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4818): GC_CONCURRENT freed 2691K, 12% free 21962K/24832K, paused 3ms+2ms, total 39ms
,D/dalvikvm( 4818): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4818): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 322K, 11% free 22316K/24832K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4818): Grow heap (frag case) to 24.007MB for 42652-byte allocation
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 103K, 11% free 22323K/24876K, paused 26ms, total 26ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 126K, 11% free 22343K/24876K, paused 41ms, total 41ms
,I/dalvikvm-heap( 4818): Grow heap (frag case) to 24.084MB for 95956-byte allocation
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 179K, 11% free 22378K/24972K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4818): Grow heap (frag case) to 24.164MB for 143930-byte allocation
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 252K, 11% free 22425K/25116K, paused 50ms, total 50ms
,I/dalvikvm-heap( 4818): Grow heap (frag case) to 24.279MB for 215890-byte allocation
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 368K, 12% free 22499K/25328K, paused 45ms, total 46ms
,I/dalvikvm-heap( 4818): Grow heap (frag case) to 24.454MB for 323830-byte allocation
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 567K, 12% free 22619K/25648K, paused 41ms, total 42ms
,I/dalvikvm-heap( 4818): Grow heap (frag case) to 24.726MB for 485740-byte allocation
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 862K, 13% free 22795K/26124K, paused 32ms, total 33ms
D/dalvikvm( 4818): GC_FOR_ALLOC freed 1175K, 12% free 23041K/26124K, paused 29ms, total 29ms
D/dalvikvm( 4818): GC_FOR_ALLOC freed 148K, 12% free 23009K/26124K, paused 29ms, total 29ms
I/dalvikvm-heap( 4818): Grow heap (frag case) to 25.685MB for 1092904-byte allocation
D/dalvikvm( 4818): GC_CONCURRENT freed 1820K, 14% free 23457K/27192K, paused 2ms+2ms, total 34ms
D/dalvikvm( 4818): GC_FOR_ALLOC freed 201K, 15% free 23353K/27192K, paused 24ms, total 24ms
I/dalvikvm-heap( 4818): Grow heap (frag case) to 26.542MB for 1639352-byte allocation
D/dalvikvm( 4818): GC_CONCURRENT freed 1815K, 17% free 23994K/28796K, paused 2ms+3ms, total 32ms
D/dalvikvm( 4818): GC_FOR_ALLOC freed 1072K, 17% free 23949K/28796K, paused 25ms, total 25ms
I/dalvikvm-heap( 4818): Grow heap (frag case) to 27.907MB for 2459024-byte allocation
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/dalvikvm( 4818): GC_CONCURRENT freed 432K, 16% free 26316K/31200K, paused 2ms+3ms, total 41ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 4078K, 20% free 24971K/31200K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4818): Grow heap (frag case) to 30.077MB for 3688532-byte allocation
,D/dalvikvm( 4818): GC_CONCURRENT freed 461K, 19% free 28324K/34804K, paused 2ms+3ms, total 49ms
,D/dalvikvm( 4818): GC_FOR_ALLOC freed 4210K, 26% free 26084K/34804K, paused 29ms, total 29ms
,W/jxcore-log( 4818): Initializing JXcore engine
,W/jxcore-log( 4818): JXcore engine is ready
,D/dalvikvm( 4818): GC_CONCURRENT freed 402K, 17% free 28888K/34804K, paused 1ms+1ms, total 27ms
,D/dalvikvm( 4818): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4818): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4818): Starting JXcore engine
,W/jxcore-log( 4818): Platform android
W/jxcore-log( 4818): 
,W/jxcore-log( 4818): Process ARCH arm
W/jxcore-log( 4818): 
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4818): JXcore Cordova bridge is ready!
I/jxcore-log( 4818): 
,W/jxcore-log( 4818): JXcore engine is started
,E/jxcore  ( 4818): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4818): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4818): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  966): Finishing activity token=Token{44266c08 ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  966): GC_FOR_ALLOC freed 1082K, 51% free 29591K/59744K, paused 68ms, total 68ms
,W/PluginManager( 4818): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 78ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{433cdc00 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  966): moveHomeStack:
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  966): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
,I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/InputMethodManagerService(  966): IME STATUS OFF
W/IInputConnectionWrapper( 4818): showStatusIcon on inactive InputConnection
,D/WeatherAncestor( 1818): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:1:29
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1818): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1818): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1818): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1818): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:1:29
D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
D/Weather.Utils( 1818): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1818): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1818): 2 : Map key string is -2
D/lim     ( 1818): 2 : time = 12:01
I/WeatherReflect( 1818): Model Name : LG-D802
D/WeatherTheme( 1818): 2 : Different view - status_min_formatted : 00 != 01
D/WeatherTheme( 1818): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1818): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1818): 2 : Fixed theme : optimus
D/WeatherTheme( 1818): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1818): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 6909K, 11% free 70757K/78628K, paused 26ms, total 26ms
,D/dalvikvm( 1488): GC_CONCURRENT freed 5513K, 9% free 60856K/66552K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/GAV2    ( 4743): Thread[GAThread,5,main]: No campaign data found.
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1488): GC_FOR_ALLOC freed 4794K, 9% free 61911K/67420K, paused 17ms, total 17ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@428d0f58 time:114842
,D/UsbSettings( 2638): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2638): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2638): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2638): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{4328ff80 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1} time:114918
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  966): Killing 4290:com.google.android.talk/u0a77 (adj 15): empty #17
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1}
,E/libEGL  ( 4818): call to OpenGL ES API with no current context (logged once per thread)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43f2bd18 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1526): onDestroy
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,E/ThermalEngine(  292): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: X
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.438705 Y: -0.424225 Z: 9.794464 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438705 .y:-0.424225 .z:9.794464
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.456085 Y: -0.409378 Z: 9.810089 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456085 .y:-0.409378 .z:9.810089
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4406): [414] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4406): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) },
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  966): battery changed pluggedType: 2
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.452042 Y: -0.402786 Z: 9.840042 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452042 .y:-0.402786 .z:9.840042
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.448761 Y: -0.406158 Z: 9.824692 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.449875 Y: -0.413925 Z: 9.824692 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.448761 .y:-0.406158 .z:9.824692
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/PowerManagerService(  966): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  966): [updateScreenState] screen on = false
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  966): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8737 usec
,D/qcom_sensors_hal(  966): hal_acquire_resources
,I/qcom_sensors_hal(  966): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  966): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  966): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  966): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  966): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  966): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  966): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.440186 Y: -0.396896 Z: 9.822220 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.454620 Y: -0.402451 Z: 9.821121 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.440186 .y:-0.396896 .z:9.822220
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.436050 Y: -0.421173 Z: 9.816711 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.436050 .y:-0.421173 .z:9.816711
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Sensors (  365): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  966): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  966): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  966): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
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
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.430344 Y: -0.407669 Z: 9.821381 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.430344 .y:-0.407669 .z:9.821381
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.444412 Y: -0.409515 Z: 9.821381 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444412 .y:-0.409515 .z:9.821381
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.448746 Y: -0.392395 Z: 9.824463 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448746 .y:-0.392395 .z:9.824463
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.441986 Y: -0.404846 Z: 9.823639 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441986 .y:-0.404846 .z:9.823639
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  966): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43179ca8)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  966): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
I/WindowManager(  966): No lock screen! windowToken=null
,D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb8b9d450
,D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.427353 Y: -0.414200 Z: 9.819641 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.427353 .y:-0.414200 .z:9.819641
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  966): handleScreenStateChanged: true
,D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2046): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  966): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  966): stopMonitoring
,D/wpa_supplicant( 2046): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131127
D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=132097
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  966): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2046): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2046): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  966): handleMessage: X
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 966
V/SRS_Proc(  276): ParamSet string: screen_state=on
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
,V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1159): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43280318 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1159): enqueuing start. mLedList.size()=2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=3
,D/WeatherAncestor( 1818): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:1:53
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1159): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 4038): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 4038): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/WeatherAncestor( 1818): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:1:53
,D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1818): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255,
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
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 231, B = 231
E/BatteryObserver( 1159): usb Uevent not necessary.
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
D/qdlights( 1159): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 225, B = 225
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 219, B = 219
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 213, B = 213
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/qdlights( 1159): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 207, B = 207
D/WifiController(  966): battery changed pluggedType: 2
,D/qdlights( 1159): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  966): Excessive delay in blankDisplay() while turning screen off: 412ms
D/qdlights( 1159): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1159): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1159): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1159): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1159): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 141, B = 141
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1159): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1159): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1159): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1159): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 111, B = 111
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1159): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1159): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1159): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1159): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1159): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1159): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1159): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 63, B = 63
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
,D/qdlights( 1159): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 57, B = 57
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 51, B = 51
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1159): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1159): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1159): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1159): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 27, B = 27
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/qdlights( 1159): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 21, B = 21
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855714225, nextTick: 5806, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qdlights( 1159): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855714273, nextTick: 5760, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  421): Reading a NULL string not supported here.
E/Parcel  (  421): Reading a NULL string not supported here.
E/Parcel  (  421): Reading a NULL string not supported here.
,E/Parcel  (  421): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:1:54
,D/WeatherService( 1818): 2 : ACTION screen on
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:1:54
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_ON
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1143): notifyScreenOffLocked
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1}
,D/qcom_sensors_hal(  966): hal_acquire_resources
,D/qcom_sensors_hal(  966): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  966): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  966): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  966): hal_smgr_report_delete: Rcvd success response from request
,I/LGImmersionVibrator(  966): Vibrator off
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/WifiStateMachine(  966): handleScreenStateChanged: false
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  966): doBoolean: DRIVER SETSUSPENDMODE 1
,I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/wpa_supplicant( 2046): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2046): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 966
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{42c7f3e0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  966): CMD_SCREEN_OFF 
D/WifiController(  966): shouldWifiStayAwake TRUE
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 1,ff00ff00,500,2000,1
,D/wpa_supplicant( 2046): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  966):    returned true
,D/WifiStateMachine(  966): handleMessage: X
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=2
D/EmotionalLed( 1159): RESTART MSG
,D/VolumeVibrator( 1159): clear
E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:1:54
,D/WeatherService( 1818): 2 : ACTION screen off
D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:1:54
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  421): Reading a NULL string not supported here.
E/Parcel  (  421): Reading a NULL string not supported here.
E/Parcel  (  421): Reading a NULL string not supported here.
,E/Parcel  (  421): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/NfcService( 1473): NFC-C OFF
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_OFF
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Sensors (  365): sns_pwr.c(320):releasing wakelock
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,E/ThermalEngine(  292): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855720044, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855720056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855731413142086; DSPS: 5275138; Offset: 1452855570428706051
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855751415262129; DSPS: 5930568; Offset: 1452855570428689864
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855771416539362; DSPS: 6585969; Offset: 1452855570428715876
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Diskstats( 1856): User is not opted-in to Usage & Diagnostics.
,D/Procstats( 1856): User is not opted-in to Usage & Diagnostics.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855780043, nextTick: 59968, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855780057, nextTick: 59976, mDrawingTime: 0
,D/wpa_supplicant( 2046): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2046): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2046): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855791419692532; DSPS: 7241433; Offset: 1452855570428695218
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855811420989086; DSPS: 7896835; Offset: 1452855570428710034
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855831422288766; DSPS: 8552238; Offset: 1452855570428697458
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855840034, nextTick: 59980, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855840058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855851424262822; DSPS: 9207662; Offset: 1452855570428718389
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855871425206095; DSPS: 9863053; Offset: 1452855570428715617
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855891426516400; DSPS: 10518456; Offset: 1452855570428713666
,D/dalvikvm( 2697): GC_CONCURRENT freed 7670K, 33% free 16863K/24832K, paused 3ms+1ms, total 33ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855900055, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855900056, nextTick: 59976, mDrawingTime: 0
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x433d0ee0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1526): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1526): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1526): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1526): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1526): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1526): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1526): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1526): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4406): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4406): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4406): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4406): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4406): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4406): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4406): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4406): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4406): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4406): isDataSchedulerEnabled():false
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855911427980298; DSPS: 11173864; Offset: 1452855570428712720
,I/LocationManagerService(  966): remove 42b112b8
,D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  966): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2697): GC_CONCURRENT freed 1803K, 32% free 17107K/24832K, paused 3ms+2ms, total 55ms
,D/dalvikvm( 2697): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 2697): GC_CONCURRENT freed 1392K, 29% free 17762K/24832K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 2697): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/Mlt MonitorService( 2697): parseLastkmsg to dump
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855931429348311; DSPS: 11829269; Offset: 1452855570428707442
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855951430625647; DSPS: 12484671; Offset: 1452855570428703040
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855960044, nextTick: 59969, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452855960057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855971431975587; DSPS: 13140075; Offset: 1452855570428710207
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452855991433266777; DSPS: 13795478; Offset: 1452855570428689141
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856011434634896; DSPS: 14450883; Offset: 1452855570428683969
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856020041, nextTick: 59966, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856020056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856031436081763; DSPS: 15106290; Offset: 1452855570428696510
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856051437361807; DSPS: 15761692; Offset: 1452855570428694815
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856071438272112; DSPS: 16417082; Offset: 1452855570428689593
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856080022, nextTick: 60003, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856080056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856091439610125; DSPS: 17072486; Offset: 1452855570428684833
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856111440950743; DSPS: 17727889; Offset: 1452855570428713195
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856131441840891; DSPS: 18383278; Offset: 1452855570428718333
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856140052, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856140056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856151442759893; DSPS: 19038669; Offset: 1452855570428691290
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856171443617126; DSPS: 19694057; Offset: 1452855570428694031
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856191444503681; DSPS: 20349446; Offset: 1452855570428695576
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856200045, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856200057, nextTick: 59974, mDrawingTime: 1
,I/ActivityManager(  966): Killing 2187:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856211447662788; DSPS: 21004909; Offset: 1452855570428711372
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856231448523196; DSPS: 21660297; Offset: 1452855570428717288
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856251449857825; DSPS: 22315701; Offset: 1452855570428709144
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856260036, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856260044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856271450781463; DSPS: 22971091; Offset: 1452855570428717255
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856291451668903; DSPS: 23626481; Offset: 1452855570428689167
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856311452517280; DSPS: 24281868; Offset: 1452855570428713570
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856320044, nextTick: 59969, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856320056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856331454523680; DSPS: 24937294; Offset: 1452855570428705809
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856351455375964; DSPS: 25592682; Offset: 1452855570428703601
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856371456673769; DSPS: 26248085; Offset: 1452855570428689150
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856380027, nextTick: 60002, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856380045, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856391458031260; DSPS: 26903489; Offset: 1452855570428703868
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856411459356670; DSPS: 27558893; Offset: 1452855570428686504
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856431460212548; DSPS: 28214280; Offset: 1452855570428718408
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856440042, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856440044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856451461707904; DSPS: 28869690; Offset: 1452855570428687885
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856471463035344; DSPS: 29525093; Offset: 1452855570428703069
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856491463868097; DSPS: 30180480; Offset: 1452855570428711847
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856500034, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856500042, nextTick: 59990, mDrawingTime: 0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  966): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  966): Done.
,D/QcConnectivityService(  966): Setting timer for 720seconds
,I/VacuumService( 1526): Vacuum at: now=1452856505134 tag=VacuumService
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1526): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1526): No account for auth token provided
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1526): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,W/Uploader( 1526): No account for auth token provided
,W/Uploader( 1526):  no longer exists, so no auth token.
,W/Uploader( 1526): No account for auth token provided
,D/dalvikvm( 1526): GC_CONCURRENT freed 1760K, 28% free 18074K/24832K, paused 14ms+5ms, total 81ms
,W/Uploader( 1526): No account for auth token provided
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856511464834809; DSPS: 30835872; Offset: 1452855570428701997
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856531466333707; DSPS: 31491281; Offset: 1452855570428705534,
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856551467216147; DSPS: 32146670; Offset: 1452855570428702964
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856560051, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856560058, nextTick: 59974, mDrawingTime: 0
,D/dalvikvm(  966): GC_CONCURRENT freed 2175K, 49% free 30577K/59744K, paused 6ms+11ms, total 196ms
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856571474747911; DSPS: 32802277; Offset: 1452855570428696886
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856591476203320; DSPS: 33457685; Offset: 1452855570428687451
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856611477055917; DSPS: 34113072; Offset: 1452855570428716074
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856620044, nextTick: 59967, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856620057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856631481905284; DSPS: 34768591; Offset: 1452855570428713146
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856651483202202; DSPS: 35423994; Offset: 1452855570428697808
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856671484332821; DSPS: 36079391; Offset: 1452855570428699277
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856680048, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856680052, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856691485367292; DSPS: 36734785; Offset: 1452855570428696150
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856711486216139; DSPS: 37390173; Offset: 1452855570428690505
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856731487495349; DSPS: 38045575; Offset: 1452855570428687976
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856740036, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856740043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856751488375864; DSPS: 38700963; Offset: 1452855570428713999
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856771488815022; DSPS: 39356338; Offset: 1452855570428695394
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856791490116108; DSPS: 40011740; Offset: 1452855570428714741
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856800036, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856800042, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856811490981048; DSPS: 40667129; Offset: 1452855570428694672
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856831491878072; DSPS: 41322518; Offset: 1452855570428706686
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856851497420929; DSPS: 41978060; Offset: 1452855570428695344
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856860028, nextTick: 59995, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856860050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856871498796286; DSPS: 42633465; Offset: 1452855570428697410
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856891500141018; DSPS: 43288869; Offset: 1452855570428699368
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856911501422052; DSPS: 43944271; Offset: 1452855570428698664
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856920029, nextTick: 59978, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856920057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856931502782930; DSPS: 44599675; Offset: 1452855570428716768
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856951504617714; DSPS: 45255096; Offset: 1452855570428689980
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856971505964633; DSPS: 45910500; Offset: 1452855570428694126
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856980034, nextTick: 59979, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452856980059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452856991507334939; DSPS: 46565905; Offset: 1452855570428691141
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857011508614514; DSPS: 47221307; Offset: 1452855570428688977
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857031509952788; DSPS: 47876711; Offset: 1452855570428684478
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857040050, nextTick: 59969, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857040056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857051511321946; DSPS: 48532115; Offset: 1452855570428710863
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857071512596522; DSPS: 49187517; Offset: 1452855570428703700
,I/EventLogService( 1856): Aggregate from 1452855603009 (log), 1452855097718 (data)
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,E/Ads     ( 1856): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857091514499119; DSPS: 49842939; Offset: 1452855570428714207
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857100034, nextTick: 59976, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857100056, nextTick: 59976, mDrawingTime: 0,
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857111515935830; DSPS: 50498347; Offset: 1452855570428686075
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857131517283219; DSPS: 51153751; Offset: 1452855570428690690
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857151518591752; DSPS: 51809154; Offset: 1452855570428686967
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857160052, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857160056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857171520009244; DSPS: 52464560; Offset: 1452855570428700651
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857191521300435; DSPS: 53119962; Offset: 1452855570428710103
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857211522596000; DSPS: 53775365; Offset: 1452855570428693413
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857220029, nextTick: 59976, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857220059, nextTick: 59973, mDrawingTime: 0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
,D/QcConnectivityService(  966): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  966): Done.
,D/QcConnectivityService(  966): Setting timer for 720seconds
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857231524577242; DSPS: 54430790; Offset: 1452855570428691012
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857251525925360; DSPS: 55086194; Offset: 1452855570428696357
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857271527211654; DSPS: 55741596; Offset: 1452855570428700912
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857280049, nextTick: 59976, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857280055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857291528766438; DSPS: 56397007; Offset: 1452855570428699300
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857311530097733; DSPS: 57052411; Offset: 1452855570428687821
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857331531384131; DSPS: 57707813; Offset: 1452855570428692481
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857340045, nextTick: 59975, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857340055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857351532748653; DSPS: 58363217; Offset: 1452855570428714230
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857371534096096; DSPS: 59018622; Offset: 1452855570428688382
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857391535485723; DSPS: 59674027; Offset: 1452855570428704718
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857400078, nextTick: 59952, mDrawingTime: 3
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857400080, nextTick: 59953, mDrawingTime: 0
I/ProcessStatsService(  966): Prepared write state in 43ms
,I/ProcessStatsService(  966): Prepared write state in 28ms
,I/ProcessStatsService(  966): Pruning old procstats: /data/system/procstats/state-2016-01-14-10-36-12.bin
,D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1526): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857411536900872; DSPS: 60329433; Offset: 1452855570428716058
,I/ActivityManager(  966): Killing 4472:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1801s
,I/ActivityManager(  966): Killing 3901:com.google.android.gms.unstable/u0a6 (adj 15): empty for 1803s
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cdf378 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857431538484250; DSPS: 60984845; Offset: 1452855570428712522
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857451539821846; DSPS: 61640249; Offset: 1452855570428707345
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857460056, nextTick: 59974, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452857460057, nextTick: 59975, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857471541224234; DSPS: 62295655; Offset: 1452855570428705924
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1452857491542508237; DSPS: 62951057; Offset: 1452855570428708189
,TIME-OUT KILL (timeout was 1800000ms)
```
