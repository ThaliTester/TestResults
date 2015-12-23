#### Test 54312298af2c956_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1846): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1846): launchTask
W/dalvikvm( 1846): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1846): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1846): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1846): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1846): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1846): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1846): No vision deps
V/ConfigFetchTask( 1846): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Uhk_aZDCx7_B5BOuDe3hue6_aVob4ep8GTb3Z0C1FsFzu8e3olVkB2dX5QLva1F_SHZonddpPTYyfUUAvEE8VbJknerC_ly9Q9MHPuBJeCOjgOLg-J4V4wDKLRusMHxQeg7jbt7zYqX8qvEk-RZsho_zHd8TQq79FameZg-Pc3f6W7Z4TpPq5hdQ2VQ8miAJ81U4sy
,I/GoogleURLConnFactory( 1846): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 1846): CP2 sync disabled
I/dalvikvm( 1846): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1846): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1846): VFY: replacing opcode 0x6e at 0x000e
D/libc    (  265): _dns_getaddrinfo: iptype =1
D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1846): Using Auth Proxy for data requests.
W/BaseAppContext( 1846): Using Auth Proxy for data requests.
W/BaseAppContext( 1846): Using Auth Proxy for data requests.
W/BaseAppContext( 1846): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1846): Using Auth Proxy for data requests.
W/GAV2    ( 4598): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/BaseAppContext( 1846): Using Auth Proxy for data requests.
I/ActivityManager(  964): Killing 4043:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2}
D/AndroidRuntime( 4637): 
D/AndroidRuntime( 4637): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4637): CheckJNI is OFF
D/dalvikvm( 4637): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4637): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4637): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4637): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4637): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4637): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/dalvikvm( 1846): GC_CONCURRENT freed 1521K, 22% free 19486K/24836K, paused 3ms+18ms, total 48ms
D/ChimeraCfgMgr( 1846): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1846): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1846): fetch service done; releasing wakelock
I/ConfigFetchService( 1846): stopping self
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/memtrack( 4637): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4637): failed to load memtrack module: -2
I/Icing   ( 1846): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1846): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4637): Calling main entry com.android.commands.am.Am
I/Icing   ( 1846): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4637
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  270): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (110 us)
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{43362f58 stackId=1, 2 tasks}
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/UsbSettingsControl( 2609): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2609): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4637): Shutting down VM
D/dalvikvm( 4637): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3742): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3742): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3742): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4665 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/dalvikvm(  271): GC_EXPLICIT freed 43K, 34% free 16472K/24836K, paused 1ms+2ms, total 21ms
D/HyLog   ( 4665): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4665): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4665): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  271): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 17ms
D/dalvikvm(  271): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 18ms
V/WebViewChromium( 4665): Binding Chromium to the background looper Looper (main, tid 1) {428e2e48}
I/chromium( 4665): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4665): Initializing chromium process, renderers=0
W/chromium( 4665): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4665): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4665): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4665): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4665): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4665): Remote Branch: 
I/Adreno-EGL( 4665): Local Patches: 
I/Adreno-EGL( 4665): Reconstruct Branch: 
I/dalvikvm( 4665): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4665): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4665): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4665): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4665): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4665): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4665): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4665): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4665): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4665): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4665): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4665): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4665): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4665): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4665): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4665): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4665): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4665): Enabling debug mode 0
W/AwContents( 4665): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +318ms
W/AwContents( 4665): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
I/ActivityManager( 4665): Timeline: Activity_idle id: android.os.BinderProxy@428e4dc0 time:111011
D/JsMessageQueue( 4665): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4665): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428e87e8
D/dalvikvm( 4665): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428e87e8
D/jxcore_app_log( 4665): JniHelper::setJavaVM(0x417a4838), pthread_self() = 1639508392
D/JX-Cordova( 4665): jxcore cordova android initializing
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3} time:111435
D/ActivityManager(  964): no-history finish of ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{42a01bf0 ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2609): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2019): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/dalvikvm( 4665): GC_CONCURRENT freed 2785K, 13% free 21833K/24836K, paused 2ms+1ms, total 38ms
D/dalvikvm( 4665): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 112K, 13% free 21830K/24836K, paused 23ms, total 23ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 116K, 12% free 21859K/24836K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 23.617MB for 96598-byte allocation
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 187K, 13% free 21885K/24932K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 23.687MB for 144892-byte allocation
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 253K, 13% free 21932K/25076K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 23.803MB for 217334-byte allocation
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 369K, 13% free 22007K/25292K, paused 38ms, total 38ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 23.980MB for 325996-byte allocation
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 568K, 14% free 22129K/25612K, paused 38ms, total 40ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 24.253MB for 488990-byte allocation
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 867K, 15% free 22306K/26092K, paused 23ms, total 23ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 1283K, 14% free 22563K/26092K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 25.261MB for 1100216-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 1675K, 16% free 22938K/27168K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 368K, 16% free 22892K/27168K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 26.107MB for 1650320-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 1897K, 19% free 23487K/28780K, paused 1ms+5ms, total 46ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 1176K, 19% free 23523K/28780K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 27.509MB for 2475476-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 1923K, 23% free 24274K/31200K, paused 2ms+2ms, total 37ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.449554 Y: -0.411987 Z: 9.749298 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449554 .y:-0.411987 .z:9.749298
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.458313 Y: -0.403625 Z: 9.745285 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458313 .y:-0.403625 .z:9.745285
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/dalvikvm( 4665): GC_CONCURRENT freed 2398K, 22% free 24479K/31200K, paused 1ms+8ms, total 54ms
,D/dalvikvm( 4665): WAIT_FOR_CONCURRENT_GC blocked 45ms
,D/dalvikvm( 4665): GC_FOR_ALLOC freed 491K, 23% free 24304K/31200K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4665): Grow heap (frag case) to 29.453MB for 3713210-byte allocation
,D/dalvikvm( 4665): GC_CONCURRENT freed 301K, 20% free 27947K/34828K, paused 2ms+3ms, total 40ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/jxcore-log( 4665): Initializing JXcore engine
W/jxcore-log( 4665): JXcore engine is ready
W/jxcore-log( 4665): Starting JXcore engine
W/jxcore-log( 4665): Platform android
W/jxcore-log( 4665): 
W/jxcore-log( 4665): Process ARCH arm
W/jxcore-log( 4665): 
,I/jxcore-log( 4665): JXcore Cordova bridge is ready!
I/jxcore-log( 4665): 
,W/jxcore-log( 4665): JXcore engine is started
,I/chromium( 4665): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4665): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4665): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
I/ActivityManager(  964): Killing 4131:com.google.android.talk/u0a77 (adj 15): empty #17
,D/wpa_supplicant( 2019): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4665): Toggling radios to true
I/jxcore-log( 4665): 
,D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4490c380:true
,D/BluetoothAdapter( 4665): enable(): BT is already enabled..!
D/WifiService(  964): New client listening to asynchronous messages
,D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
,I/jxcore-log( 4665): Radios toggled
I/jxcore-log( 4665): 
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2019): TDLS: Tear down peers
,D/wpa_supplicant( 2019): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4665): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4665): 
,I/jxcore-log( 4665): Perf Test app loaded loaded
I/jxcore-log( 4665): 
D/WifiService(  964): setWifiEnabled: true pid=4665, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  964): disconnect pid=4665, uid=10304
,D/WifiService(  964): reconnect pid=4665, uid=10304
I/Choreographer( 4665): Skipped 63 frames!  The application may be doing too much work on its main thread.
,D/wpa_supplicant( 2019): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2019): wlan0: Deauthentication notification
D/wpa_supplicant( 2019): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2019): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2019): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Auto connect disabled: do not try to re-connect
,D/wpa_supplicant( 2019): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2019): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 2019): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb79d2d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2019):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 2019): nl80211: Ignore disconnect event triggered during reassociation
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2019): Fast associate: Old scan results
D/wpa_supplicant( 2019): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2019): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2019): wlan0: nl80211: scan request
D/wpa_supplicant( 2019): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2019): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2019): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
I/chromium( 4665): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
I/jxcore-log( 4665): check test folder
I/jxcore-log( 4665): 
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
I/jxcore-log( 4665): found test : ./testFindPeers.js
I/jxcore-log( 4665): 
,D/DhcpStateMachine(  964): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  265): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/QCNEA   (  602): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  602): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  602): |CAC| updateNetCfgInfo
V/QCNEA   (  602): |CAC| *********************************************
V/QCNEA   (  602): |CAC|                   Netconfig               
V/QCNEA   (  602): |CAC| *********************************************
V/QCNEA   (  602): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  602): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  602): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  602): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  602): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  602): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  602): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  602): |CAC| *********************************************
D/QCNEA   (  602): |CAC| Received bssid= 
D/QCNEA   (  602): |CAC| net type = 3
V/QCNEA   (  602): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  602): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  602): |CAC| 	ssid           =NG700
V/QCNEA   (  602): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  602): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  602): |CAC| *********************************************
D/QCNEA   (  602): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  602): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  602): |CAC| dispatchNetCfg: updating:0xb7cfa8dc
,D/QCNEA   (  602): |CAC| readCallback: read len:0, ret:-1, errno:11
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiHS20(  964): hidePasspointNotification off =false
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
I/jxcore-log( 4665): found test : ./testSendData.js
I/jxcore-log( 4665): 
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  265): RouteController
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4720 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/GAV2    ( 4598): Thread[GAThread,5,main]: No campaign data found.
V/        (  265): RouteController
V/        (  265): RouteController
D/HyLog   ( 4720): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4720): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4720): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  265): RouteController
,V/        (  265): RouteController
,I/PCSuite ( 4720): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  265): RouteController
,V/        (  265): RouteController
D/PCSuite ( 4720): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4720): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  265): RouteController
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/NetworkManagementService(  964): route cmd failed: 
W/NetworkManagementService(  964): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  964): '
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  964): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  964): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  964): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  964): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  964): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  964): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x629ff2f8 clazz=0x6c500001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,I/jxcore-log( 4665): found test : ./testSendData2.js
I/jxcore-log( 4665): 
,V/NativeCrypto( 1546): Read error: ssl=0x63985d38: I/O error during system call, Connection timed out
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4750 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 2140:android.process.media/u0a23 (adj 15): empty #17
,V/NativeCrypto( 1546): SSL shutdown failed: ssl=0x63985d38: I/O error during system call, Broken pipe
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 4750): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4750): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4750): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QRemote ( 4750): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4750): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4750): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4750): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4750): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4750): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4750): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4750): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 3919:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DhcpStateMachine(  964): StoppedState
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1546): onDestroy
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] connect :false
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2019): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2019): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2019): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2019): nl80211: Survey data missing
D/wpa_supplicant( 2019): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2019): wlan0: BSS: Add new id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Add new id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2019): wlan0: New scan results available
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2019): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2019): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2019): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2019): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2019): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 2019): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2019): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62 wps
D/wpa_supplicant( 2019): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2019): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2019): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb79d45a8  current_ssid=0x0
D/wpa_supplicant( 2019): scard is not null..
D/wpa_supplicant( 2019): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2019): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a ,01 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2019): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2019): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2019): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2019): RSN: PMKSA cache search - network_ctx=0xb79d45a8 try_opportunistic=0
D/wpa_supplicant( 2019): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2019): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2019): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2019): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2019): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2019): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2019): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2019): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2019): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2019): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2019): nl80211: Unsubscribe mgmt frames handle 0xb79d3590 (mode change)
D/wpa_supplicant( 2019): nl80211: Subscribe to mgmt frames with non-AP handle 0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2019): nl80211: Register frame type=0xd0 nl_handle=0xb79d3590
D/wpa_supplicant( 2019): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2019): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2019):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019):   * freq=2412
D/wpa_supplicant( 2019):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2019):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019):   * Auth Type 0
D/wpa_supplicant( 2019):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 a0:c5:62:7a:49:97]
D/wpa_supplicant( 2019): nl80211: Connect request send successfully
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2019): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2019): nl80211: Event message available
D/wpa_supplicant( 2019): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2019): nl80211: Connect event
D/wpa_supplicant( 2019): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2019): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2019): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2019): wlan0: Association info event
D/wpa_supplicant( 2019): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2019): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2019): wlan0: freq=2412 MHz
D/wpa_supplicant( 2019): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2019): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2019): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2019): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): scard is not null..
D/wpa_supplicant( 2019): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2019): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2019): TDLS: Remove peers on association
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2019): EAPOL: enable timer tick
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): wlan0: Cancelling scan request
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2019): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a3 cb 64 67 32 f1 58 32 01 e8 27 03 e8 f0 51 ...
D/wpa_supplicant( 2019): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2019): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2019): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2019): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2019): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2019):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2019):   key_nonce - hexdump(len=32): a3 cb 64 67 32 f1 58 32 01 e8 27 03 e8 f0 51 46 3d bc 74 24 5f 51 b4 6d bd 7f d6 96 b5 20 19 e0
D/wpa_supplicant( 2019):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 a3 cb 64 67 32 f1 58 32 01 e8 27 03 e8 f0 51 ...
D/wpa_supplicant( 2019): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2019): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2019): Get randomness: len=32 entropy=5
D/wpa_supplicant( 2019): WPA: Renewed SNonce - hexdump(len=32): 12 36 5c 08 5e 5e 4d b8 64 ca ca 16 b1 b8 00 2d 3e 59 a6 de 8a 1c 13 ab 37 15 ae 21 2f 2d e2 10
D/wpa_supplicant( 2019): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): WPA: Nonce1 - hexdump(len=32): 12 36 5c 08 5e 5e 4d b8 64 ca ca 16 b1 b8 00 2d 3e 59 a6 de 8a 1c 13 ab 37 15 ae 21 2f 2d e2 10
D/wpa_supplicant( 2019): WPA: Nonce2 - hexdump(len=32): a3 cb 64 67 32 f1 58 32 01 e8 27 03 e8 f0 51 46 3d bc 74 24 5f 51 b4 6d bd 7f d6 96 b5 20 19 e0
D/wpa_supplicant( 2019): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2019): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2019): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2019): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2019): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): WPA: Derived Key MIC - hexdump(len=16): 19 3f 83 8c e2 36 4d 1b bd cc 91 9c 45 1a f6 e0
D/wpa_supplicant( 2019): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 12 36 5c 08 5e 5e 4d b8 64 ca ca 16 b1 b8 00 ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2019): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a3 cb 64 67 32 f1 58 32 01 e8 27 03 e8 f0 51 ...
D/wpa_supplicant( 2019): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2019): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2019): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2019): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2019):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2019):   key_nonce - hexdump(len=32): a3 cb 64 67 32 f1 58 32 01 e8 27 03 e8 f0 51 46 3d bc 74 24 5f 51 b4 6d bd 7f d6 96 b5 20 19 e0
D/wpa_supplicant( 2019):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_rsc - hexdump(len=8): a3 7c 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2019):   key_mic - hexdump(len=16): e1 e7 cb 6c 99 b0 86 78 6b 86 4e 30 4c 58 f5 00
D/wpa_supplicant( 2019): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 a3 cb 64 67 32 f1 58 32 01 e8 27 03 e8 f0 51 ...
D/wpa_supplicant( 2019): RSN: encrypted key data - hexdump(len=56): 34 2c a5 2f 0b 08 d6 04 83 ac 2b 9e ed c1 86 39 3b 89 e5 a7 e9 1c 46 7e b5 59 cc 90 41 b2 bd 2b ...
D/wpa_supplicant( 2019): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2019): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2019): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2019): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 e5 4a ...
D/wpa_supplicant( 2019): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2019): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2019): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2019): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): WPA: Derived Key MIC - hexdump(len=16): 03 10 d5 77 49 d3 57 75 38 49 52 bb d7 ad 31 c0
D/wpa_supplicant( 2019): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2019): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb79d3c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2019):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2019): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2019): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2019): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2019): WPA: RSC - hexdump(len=6): a3 7c 00 00 00 00
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2c03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2019):    broadcast key
I/wpa_supplicant( 2019): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2019): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2019): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2019): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2019): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2019): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2019): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2019): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2019): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2019): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2019): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2019): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2019): EAPOL authentication completed successfully
D/wpa_supplicant( 2019): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2019): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2019): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection established
D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2019): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  964): ssid=NG700
D/WifiNative-wlan0(  964): id=0
D/WifiNative-wlan0(  964): mode=station
D/WifiNative-wlan0(  964): pairwise_cipher=CCMP
D/WifiNative-wlan0(  964): group_cipher=CCMP
D/WifiNative-wlan0(  964): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  964): wpa_state=COMPLETED
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
,E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
,E/Parcel  (  602): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  964): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-34ms what=147462 obj=android.net.wifi.StateChangeResult@43e4b0f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): ObtainingIpState{ when=-40ms what=147462 obj=android.net.wifi.StateChangeResult@442f8490 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
,D/WifiStateMachine(  964): processMsg: ObtainingIpState
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  964): ObtainingIpState{ when=-39ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-18ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
I/AppUp4:CustModeStarterReceiver( 4007): onReceive
D/wpa_supplicant( 2019): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-20ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/AppUp4:CustFacade( 4007): Context : android.app.ReceiverRestrictedContext@428f7270
D/AppUp4:CustFacade( 4007): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4007): isOpenOperator : true
D/AppUp4:CustFacade( 4007): isPhone : true
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/LicenseContentProvider( 2975): start selecting data
D/SIMObserver( 2975): simInfo1
I/AppUp4:EulaManager( 4007): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4007): begin check event
I/AppUp4:CustModeStarterReceiver( 4007): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4793 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4793): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4793): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,D/CommandListener(  265): Setting iface cfg
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4329fe60 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4329fe60 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  265): Trying to bring up wlan0
D/WifiStateMachine(  964): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/EAS     ( 4578): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4578): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4793): DownloadService onCreate
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2019): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2019): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2019): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/eas_req ( 4578): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 4793): in removeSpuriousFiles
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
,D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  964): send additional Connectivity Action
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
,D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,V/DownloadManager( 4793): DownloadService onStartCommand
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): handleMessage: X
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  602): Reading a NULL string not supported here.
,E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/LgeMiscReceiver( 4313): networkInfo.isConnected() = false
,D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
V/DownloadManager( 4793): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/DownloadManager( 4793): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42920490 on behalf of 4793
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@429209b8 on behalf of 4793
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/DownloadManager( 4793): in trimDatabase
V/DownloadManager( 4793): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@429229a0 on behalf of 4793
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4815 uid=10052 gids={50052, 3003}
,E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
,W/linker  ( 4578): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 4578): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4578): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4578): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4578): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4578): register_HtmlEditor, Success
,D/HtmlEditor( 4578): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4578): register_HtmlEditorTimer, Success
D/HtmlEditor( 4578): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4578): register_HtmlEditorDownloader, Success
,D/HtmlEditor( 4578): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4578): register_HtmlEditorFont, Success
D/HtmlEditor( 4578): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4578): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4578): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
D/HtmlEditor( 4578): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4578): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4578): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4578): JNI_OnLoad Success
V/DownloadManager( 4793): DownloadService onDestroy
I/HubEmail( 4578): JNI_OnLoad()
I/HubEmail( 4578): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4578): registerNatives()
I/HubEmail( 4578): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4578): registerNativeMethods()
I/HubEmail( 4578): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
V/        (  265): RouteController
W/Settings( 4578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  265): RouteController
D/HyLog   ( 4815): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  265): RouteController
,V/        (  265): RouteController
,V/        (  265): RouteController
I/ActivityManager(  964): Killing 4299:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,V/        (  265): RouteController
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  265): RouteController
V/        (  265): RouteController
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4815): [loadRssi] File not exist 
V/LGRssiData( 4815): [loadRssi] File not exist 
V/        (  265): RouteController
V/TelephonyAutoProfiling( 4815): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4815): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4815): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4815): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4815): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4815): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4815): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4815): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4815): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/QCNEA   (  602): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  602): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  602): |CAC| updateNetCfgInfo
V/QCNEA   (  602): |CAC| *********************************************
V/QCNEA   (  602): |CAC|                   Netconfig               
V/QCNEA   (  602): |CAC| *********************************************
,V/QCNEA   (  602): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  602): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  602): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  602): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  602): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  602): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  602): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  602): |CAC| *********************************************
D/QCNEA   (  602): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  602): |CAC| net type = 1
V/QCNEA   (  602): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  602): |CAC| Received ssid= NG700
V/QCNEA   (  602): |CAC| 	ssid           =NG700
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  602): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  602): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  602): |CAC| *********************************************
D/QCNEA   (  602): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  602): |CAC| dispatching netcfgupdate for wlan
,D/QCNEA   (  602): |CAC| dispatchNetCfg: updating:0xb7cfa8dc
D/QCNEA   (  602): |CAC| readCallback: read len:0, ret:-1, errno:11
D/MobileConnectivityChangeReceiver( 4815): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4850 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 4815): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4815): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  964): Killing 4502:com.android.defcontainer/u0a4 (adj 15): empty #17
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4850): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1846): Checking schedule, now: 1450836526849 next: 1450836469160
I/CheckinService( 1846): active receiver: enabled
,I/CheckinService( 1846): Preparing to send checkin request
,I/EventLogService( 1846): Accumulating logs since 1450836436680
,D/DhcpStateMachine(  964): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  964): GC_EXPLICIT freed 23509K, 49% free 29698K/57688K, paused 3ms+8ms, total 125ms
,I/CheckinRequestBuilder( 1846): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4874 uid=10066 gids={50066, 4002, 3003, 1028}
,E/ActivityThread( 1846): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4874): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 4543:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2864): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2864): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2864): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2864): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/dalvikvm( 1546): GC_EXPLICIT freed 1124K, 29% free 17815K/24836K, paused 1ms+3ms, total 30ms
,I/LGDMClient( 2864): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4887 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4887): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4887): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4887): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4887): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4887): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4901 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 4565:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4901): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4901): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4901): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 4901): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4901): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4901): intf.getDisplayName() = lo
I/Wireless_Storage( 4901): intf.getDisplayName() = sit0
I/Wireless_Storage( 4901): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4901): intf.getDisplayName() = teql0
I/Wireless_Storage( 4901): intf.getDisplayName() = wlan0
,D/NFS     ( 4901): interface name:wlan0 name:wlan0
D/NFS     ( 4901): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4901): interface name:wlan0 name:wlan0
D/NFS     ( 4901): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4901): CONNECT : WIFI_CONNECT
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4914 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4180:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
,D/HyLog   ( 4914): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4914): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4914): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 4914): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/CheckinRequestBuilder( 1846): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x433da9c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4932 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4932): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4932): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4932): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4932): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4932): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4932): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4932): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4932): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4932): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4932): install
,I/MultiDex( 4932): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4932): loading existing secondary dex files
,I/MultiDex( 4932): load found 3 secondary dex files
,I/MultiDex( 4932): install done
,D/dalvikvm( 4932): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4932): VFY: unable to resolve instance field 61
D/dalvikvm( 4932): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 4932): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4932): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4932): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4932): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4932): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4932): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4932): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4932): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4932): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e8990
D/dalvikvm( 4932): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e8990
,D/dalvikvm( 4932): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e8990, skipping init
,D/dalvikvm( 4932): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428e8990
D/dalvikvm( 4932): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428e8990
,V/JNIHelp ( 4932): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4932): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e8990
,D/dalvikvm( 4932): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428e8990
D/dalvikvm( 4932): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428e8990
,D/dalvikvm( 4932): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428e8990
,V/WebViewChromium( 4914): Binding Chromium to the main looper Looper (main, tid 1) {428e1708}
,I/chromium( 4914): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4914): Initializing chromium process, renderers=0
,W/chromium( 4914): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4914): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4914): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4914): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4914): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4914): Remote Branch: 
I/Adreno-EGL( 4914): Local Patches: 
I/Adreno-EGL( 4914): Reconstruct Branch: 
,I/ProviderInstaller( 4932): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4932): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4932): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4932): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4932): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4932): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4932): VFY: replacing opcode 0x6e at 0x0201
,I/NSApplication( 4914): Starting up...
,I/ActivityManager(  964): Killing 4196:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3}
,D/WVCdm   (  273): Instantiating CDM.
,I/WVCdm   (  273): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  273): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  273): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  273): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fcc000
,E/DrmWidevineDash(  273): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fcc000
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4750): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DrmWidevineDash(  273): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  273): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  273): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  273): calling OEMCrypto_IsKeyboxValid...
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4750): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/DrmWidevineDash(  273): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  273): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/WVCdm   (  273): CdmEngine::OpenSession
D/DrmWidevineDash(  273): calling OEMCrypto_OpenSession...
,I/QRemote ( 4750): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
I/PCSuite ( 4720): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4720): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 4750): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DrmWidevineDash(  273): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  273): OEMCrypto_OpenSession returns 0
I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  273): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/QRemote ( 4750): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4750): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4750): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/wpa_supplicant( 2019): EAPOL: startWhen --> 0
D/wpa_supplicant( 2019): EAPOL: disable timer tick
D/GCM     ( 1546): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/DrmWidevineDash(  273): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  273): calling OEMCrypto_GetDeviceID...
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AuthorizationBluetoothService( 1546): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1546): Proximity feature is not enabled.
V/GmsCoreStatsServiceLauncher( 1846): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/DrmWidevineDash(  273): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  273): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  273): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  273): PrepareKeyRequest: nonce=3845363796
,D/DrmWidevineDash(  273): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WearableService( 1747): callingUid 10006, callindPid: 1747
D/DrmWidevineDash(  273): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  273): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  273): calling OEMCrypto_GenerateRSASignature. SID = 1
,E/MDM     ( 1424): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1846): Restart initialization of location
,D/dalvikvm( 4932): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a798e0
D/dalvikvm( 4932): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a798e0
,D/dalvikvm( 4932): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a798e0, skipping init
,D/DrmWidevineDash(  273): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  273): CdmEngine::CloseSession
,D/DrmWidevineDash(  273): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  273): OEMCrypto_CloseSession returns 0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4932): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/WVCdm   (  273): CdmEngine::OpenSession
,D/DrmWidevineDash(  273): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  273): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  273): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  273): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  273): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  273): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  273): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  273): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  273): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  273): calling OEMCrypto_GenerateNonce. SID = 1
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  273): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  273): PrepareKeyRequest: nonce=1169930209
,D/DrmWidevineDash(  273): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  273): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  273): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  273): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/WifiStateMachine(  964): handleMessage: X
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  273): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  273): CdmEngine::CloseSession
,D/DrmWidevineDash(  273): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  273): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4932): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/dalvikvm( 4665): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4665): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4665): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4665): Shutting down VM
,W/dalvikvm( 4665): threadid=1: thread exiting with uncaught exception (group=0x4189fe48)
E/AndroidRuntime( 4665): FATAL EXCEPTION: main
E/AndroidRuntime( 4665): Process: com.test.thalitest, PID: 4665
E/AndroidRuntime( 4665): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4665): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4665): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4665): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4665): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4665): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4665): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4665): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4665): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4665): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4665): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4665): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4665): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4665): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4665): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4665): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4665): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4665): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4665): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  964):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm( 4980): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4932): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4932): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 180ms
,I/Adreno-EGL( 4932): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4932): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4932): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4932): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4932): Remote Branch: 
I/Adreno-EGL( 4932): Local Patches: 
I/Adreno-EGL( 4932): Reconstruct Branch: 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Adreno-EGL( 4932): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4932): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4932): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4932): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4932): Remote Branch: 
I/Adreno-EGL( 4932): Local Patches: 
I/Adreno-EGL( 4932): Reconstruct Branch: 
,I/Adreno-EGL( 4932): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4932): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4932): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4932): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4932): Remote Branch: 
I/Adreno-EGL( 4932): Local Patches: 
I/Adreno-EGL( 4932): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1846): Classify the device as Phone.
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,W/ActivityManager(  964): Activity pause timeout for ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43362f58 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  964): moveHomeStack:
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  964): resumeTopActivityLocked: Resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1818): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:8:48
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1818): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1818): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1818): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1818): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:8:48
,D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1818): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1818): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1818): 2 : Map key string is -2
,D/lim     ( 1818): 2 : time = 03:08
I/WeatherReflect( 1818): Model Name : LG-D802
D/WeatherTheme( 1818): 2 : Different view - status_min_formatted : 07 != 08
,D/WeatherTheme( 1818): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1818): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1818): 2 : Fixed theme : optimus
,D/WeatherTheme( 1818): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1818): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinTask( 1846): Sending checkin request (11619 bytes)
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1487): GC_CONCURRENT freed 5536K, 9% free 60844K/66572K, paused 2ms+4ms, total 36ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1140): GC_CONCURRENT freed 4121K, 7% free 71189K/76328K, paused 3ms+6ms, total 50ms
,D/dalvikvm( 1140): WAIT_FOR_CONCURRENT_GC blocked 43ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
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
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/CheckinRequestBuilder( 1846): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1846): Failed to find provider info for com.google.android.wearable.settings
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1} time:120852
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 5010K, 9% free 61988K/67728K, paused 31ms, total 31ms
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1846): awaiting user notification for token
,I/CheckinRequestBuilder( 1846): Classify the device as Phone.
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@428ddf48 time:120983
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2609): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/UsbSettings( 2609): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2609): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2609): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/dalvikvm(  964): GC_CONCURRENT freed 2198K, 47% free 30813K/57688K, paused 3ms+6ms, total 112ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 52ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 106ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 53ms
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{431f17f0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x44ef8d20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinTask( 1846): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1846): Checking schedule, now: 1450836529546 next: 1451413925542
,I/CheckinService( 1846): active receiver: disabled
,D/GCM     ( 1546): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  602): Reading a NULL string not supported here.
,E/Parcel  (  602): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] BroadcastReceiver onReceive
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4007): onReceive
,D/AppUp4:CustFacade( 4007): Context : android.app.ReceiverRestrictedContext@428f7270
D/AppUp4:CustFacade( 4007): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4007): isOpenOperator : true
,D/AppUp4:CustFacade( 4007): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/SIMObserver( 2975): simInfo1
,I/AppUp4:EulaManager( 4007): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4007): begin check event
,I/AppUp4:CustModeStarterReceiver( 4007): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4007): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4007): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4007): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4007): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4007): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4793): DownloadService onCreate
,D/EAS     ( 4578): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 4793): in removeSpuriousFiles
,D/EAS     ( 4578): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4793): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42928690 on behalf of 4793
,D/eas_req ( 4578): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4793): in trimDatabase
,V/DownloadManager( 4793): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42929fa8 on behalf of 4793
,I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4793): DownloadService onStartCommand
,I/LgeMiscReceiver( 4313): networkInfo.isConnected() = false
,W/Settings( 4578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4793): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 4815): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4815): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@4292c238 on behalf of 4793
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/GCM     ( 1546): Connected
,D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4793): DownloadService onDestroy
,D/LGDMSGCM( 4887): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4887): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4901): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4901): CONNECT : WIFI_CONNECT
I/LGDMClient( 2864): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,E/LGDMClient( 2864): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2864): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2864): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1546): Message class com.google.f.a.a.p
,I/LGDMClient( 2864): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4007): onReceive
,D/AppUp4:CustFacade( 4007): Context : android.app.ReceiverRestrictedContext@428f7270
D/AppUp4:CustFacade( 4007): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4007): isOpenOperator : true
,D/AppUp4:CustFacade( 4007): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/SIMObserver( 2975): simInfo1
,I/AppUp4:EulaManager( 4007): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4007): begin check event
,I/AppUp4:CustModeStarterReceiver( 4007): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4793): DownloadService onCreate
,D/EAS     ( 4578): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4578): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4793): in removeSpuriousFiles
,V/DownloadManager( 4793): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42930958 on behalf of 4793
,V/DownloadManager( 4793): DownloadService onStartCommand
I/DownloadManager( 4793): in trimDatabase
,V/DownloadManager( 4793): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4793): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42933ac0 on behalf of 4793
I/LgeMiscReceiver( 4313): networkInfo.isConnected() = true
,D/PhoneState( 4313): setPdpRejectCasuse : false
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42933080 on behalf of 4793
,W/Settings( 4578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4815): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4815): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4793): DownloadService onDestroy
,D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4887): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2864): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4887): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4901): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4901): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2864): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2864): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2864): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2864): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4007): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4007): onReceive
,D/AppUp4:CustFacade( 4007): Context : android.app.ReceiverRestrictedContext@428f7270
D/AppUp4:CustFacade( 4007): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4007): isOpenOperator : true
,D/AppUp4:CustFacade( 4007): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/SIMObserver( 2975): simInfo1
,I/AppUp4:EulaManager( 4007): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4007): begin check event
,I/AppUp4:CustModeStarterReceiver( 4007): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4578): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4793): DownloadService onCreate
,D/EAS     ( 4578): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4313): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4313): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4313): networkInfo.isConnected() = true
,D/PhoneState( 4313): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4815): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4815): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2864): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4887): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4887): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4901): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4901): CONNECT : WIFI_CONNECT
,W/Settings( 4578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4793): in removeSpuriousFiles
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMClient( 2864): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/DownloadManager( 4793): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 2864): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42938688 on behalf of 4793
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/DownloadManager( 4793): in trimDatabase
V/DownloadManager( 4793): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4793): DownloadService onStartCommand
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42939f60 on behalf of 4793
V/DownloadManager( 4793): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 2864): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@4293bc98 on behalf of 4793
D/LGDMClient( 2864): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2864): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4793): DownloadService onDestroy
I/LGDMClient( 2864): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4914): Thread[GAThread,5,main]: No campaign data found.
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  964): Killing 4598:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  964): Killing 4720:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): Killing 4212:com.android.vending/u0a50 (adj 15): empty #18
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2019): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  964): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5110 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 5110): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5110): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5110): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  271): GC_EXPLICIT freed 45K, 34% free 16472K/24836K, paused 3ms+8ms, total 57ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  271): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+2ms, total 23ms
,D/dalvikvm(  271): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+3ms, total 18ms
,I/dalvikvm( 5110): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 5110): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5110): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 5110): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5110): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5110): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5110): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5110): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
E/BatteryObserver( 1154): usb Uevent not necessary.
,W/Settings( 5110): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5110): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm( 5110): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5110): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5110): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5110): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5110): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5110): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5110): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5110): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5110): VFY: replacing opcode 0x6e at 0x029a
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/DownloadManager( 4793): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
I/dalvikvm( 5110): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5110): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5110): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4793): created cursor android.database.sqlite.SQLiteCursor@42940e38 on behalf of 5110
,I/dalvikvm( 5110): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5110): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5110): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5110): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5110): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5110): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5110): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/dalvikvm( 5110): Total arena pages for JIT: 11
,I/dalvikvm( 5110): Total arena pages for JIT: 12
,I/dalvikvm( 5110): Total arena pages for JIT: 13
,I/dalvikvm( 5110): Total arena pages for JIT: 14
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5110): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5110): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  964): Killing 4750:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.472610 Y: -0.409317 Z: 9.750153 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.472610 .y:-0.409317 .z:9.750153
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.456009 Y: -0.400787 Z: 9.752808 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456009 .y:-0.400787 .z:9.752808
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5110): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5110): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5110): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5110): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5110): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1546): GC_EXPLICIT freed 1290K, 29% free 17812K/24836K, paused 2ms+4ms, total 34ms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Finsky  ( 5110): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1154): GC_CONCURRENT freed 2897K, 11% free 25448K/28528K, paused 2ms+1ms, total 25ms
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5110): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5110): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5110): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5110): [1] DailyHygiene.reschedule: Scheduling new run in 96 minutes (failures=3)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5193 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3742): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3742): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 5193): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5193): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5193): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5193): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5193): MmsConfig.loadMmsSettings
,I/Babel   ( 5193): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5193): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5193): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5193): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5193): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5193): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5193): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5193): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5193): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5193): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5193): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5193): MmsConfig.loadFromResources
,E/Babel   ( 5193): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5193): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1424): DISABLE
,W/Settings( 5193): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5193): [loadRssi] File not exist 
V/LGRssiData( 5193): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5193): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5193): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5193): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5193): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4007): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4007): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4007): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/LocationProviderProxy(  964): applying state to connected service
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm(  964): GC_EXPLICIT freed 2491K, 47% free 30675K/57016K, paused 3ms+8ms, total 101ms
,I/AppUp4:CustModeStarterReceiver( 4007): onReceive
,D/AppUp4:CustFacade( 4007): Context : android.app.ReceiverRestrictedContext@428f7270
D/AppUp4:CustFacade( 4007): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4007): isOpenOperator : true
,D/AppUp4:CustFacade( 4007): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/SIMObserver( 2975): simInfo1
,D/LocationProviderProxy(  964): applying state to connected service
,I/AppUp4:EulaManager( 4007): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4007): begin check event
D/AppUp4:Utils( 4007): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4007): Event For Nothing, skip.
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5244 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5244): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5244): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5244): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5244): BUILD Country: EU
,I/SystemConfig( 5244): BUILD Operator: OPEN
,I/SystemConfig( 5244): systemFeature RCS result false
,D/SystemConfig( 5244): refreshRcsSupport() :false
I/ActivityManager(  964): Killing 4665:com.test.thalitest/u0a304 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5259 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  964): Killing 4578:com.lge.email/u0a24 (adj 15): empty #17
,D/HyLog   ( 5259): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5259): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5259): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,I/WindowState(  964): WIN DEATH: Window{43e7f650 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  964): Client connection lost with reason: 4
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43e81ba0 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,I/InputMethodManagerService(  964): IME STATUS OFF
,W/Binder  ( 1306): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1306): java.lang.NullPointerException
W/Binder  ( 1306): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1306): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1306): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1306): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4665 uid 10304
,I/ActivityManager(  964): Killing 4815:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2678): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c86d00 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1846): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1846): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{44f7bf08 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1846): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1846): GC_CONCURRENT freed 1904K, 22% free 19577K/24836K, paused 2ms+4ms, total 39ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/IcingCorporaProvider( 2678): UpdateCorporaTask done [took 216 ms] updated apps [took 216 ms] 
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  265): _dns_getaddrinfo: iptype =1
D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/WeatherService( 1818): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:9:0
,D/WeatherService( 1818): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1818): 2 : SDK version : 19
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0,
,D/Weather.Utils( 1818): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836540032, nextTick: 59998, mDrawingTime: 1
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836540043, nextTick: 59989, mDrawingTime: 0
,D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1818): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1818): 2 : Map key string is -2
,D/lim     ( 1818): 2 : time = 03:09
,I/WeatherReflect( 1818): Model Name : LG-D802
,D/WeatherTheme( 1818): 2 : Different view - status_min_formatted : 08 != 09
,D/WeatherTheme( 1818): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1818): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1818): 2 : Fixed theme : optimus
,D/WeatherTheme( 1818): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1818): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:9:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV4    ( 5193): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8552 usec
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.482712 Y: -0.397385 Z: 9.740372 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.482712 .y:-0.397385 .z:9.740372
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  964): hal_acquire_resources
I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.475433 Y: -0.405548 Z: 9.751892 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.475433 .y:-0.405548 .z:9.751892
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  322): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.461304 Y: -0.403091 Z: 9.768173 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461304 .y:-0.403091 .z:9.768173
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.468964 Y: -0.380768 Z: 9.778625 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468964 .y:-0.380768 .z:9.778625
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.461884 Y: -0.401794 Z: 9.752274 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461884 .y:-0.401794 .z:9.752274
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.451569 Y: -0.405731 Z: 9.777237 
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.464905 Y: -0.394608 Z: 9.751663 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.451569 .y:-0.405731 .z:9.777237
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.468689 Y: -0.411072 Z: 9.753708 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468689 .y:-0.411072 .z:9.753708
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@4315d510)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
D/SurfaceFlinger(  270): Screen released, type=0 flinger=0xb75fd450
D/qdhwcomposer(  270): hwc_blank: Blanking display: 0
D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
I/WindowManager(  964): No lock screen! windowToken=null
,E/SlideAside( 3742): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  964): handleScreenStateChanged: true
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2019): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2019): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2019): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2019): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
,V/SRS_Proc(  273): ParamSet string: screen_state=on
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=on
V/voice   (  273): voice_set_parameters: enter: screen_state=on
,V/voice   (  273): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  273): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  273): adev_set_parameters: exit with code(-2)
,I/SlideAside( 3742): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{428e1758 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/WeatherAncestor( 1818): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 3:9:6
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/WeatherAncestor( 1818): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 3:9:6
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1818): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
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
,D/qdhwcomposer(  270): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 383ms
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836547194, nextTick: 52839, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.462204 Y: -0.405060 Z: 9.762604 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462204 .y:-0.405060 .z:9.762604
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836547249, nextTick: 52783, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.462524 Y: -0.395554 Z: 9.780792 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462524 .y:-0.395554 .z:9.780792
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
,E/Parcel  (  602): Reading a NULL string not supported here.
D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:9:7
D/WeatherService( 1818): 2 : ACTION screen on
D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:9:7
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1}
I/LGImmersionVibrator(  964): Vibrator off
I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
D/WifiStateMachine(  964): handleScreenStateChanged: false
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  273): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
V/SRS_Proc(  273): ParamSet string: screen_state=off
D/WifiStateMachine(  964): handleMessage: X
D/audio_hw_primary(  273): adev_set_parameters: enter: screen_state=off
,V/voice   (  273): voice_set_parameters: enter: screen_state=off
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
V/voice   (  273): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  273): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  273): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  273): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  273): adev_set_parameters: exit with code(-2)
D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
D/wpa_supplicant( 2019): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2019): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1154): clear
,V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{432015e8 u0 com.lge.launcher2/.Launcher t1} (stop complete)
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
D/wpa_supplicant( 2019): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:9:7
D/WeatherService( 1818): 2 : ACTION screen off
D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:9:7
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
E/Parcel  (  602): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleCon,troller onAction action = android.intent.action.SCREEN_OFF
D/NfcService( 1474): NFC-C OFF
D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
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
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  322): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,E/ThermalEngine(  287): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1546): Vacuum at: now=1450836556124 tag=VacuumService
,I/GoogleURLConnFactory( 1546): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1546): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1546): No account for auth token provided
I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5110): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5110): [1] 5.onFinished: Installation state replication succeeded.
,W/Uploader( 1546):  no longer exists, so no auth token.
,W/Uploader( 1546): No account for auth token provided
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836565159061190; DSPS: 5273501; Offset: 1450836404224582431
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836585160441622; DSPS: 5928907; Offset: 1450836404224559054
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836600054, nextTick: 59976, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836600057, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836605161813736; DSPS: 6584312; Offset: 1450836404224557877
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836625162259842; DSPS: 7239686; Offset: 1450836404224576737
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836645162708061; DSPS: 7895061; Offset: 1450836404224567192
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836660039, nextTick: 59991, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836660041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836665163181839; DSPS: 8550436; Offset: 1450836404224583207
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836685164086562; DSPS: 9205826; Offset: 1450836404224572402
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836705164947951; DSPS: 9861214; Offset: 1450836404224579299
,D/wpa_supplicant( 2019): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2019): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2019): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836720042, nextTick: 59983, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836720048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836725165410954; DSPS: 10516589; Offset: 1450836404224584538
,D/dalvikvm( 2664): GC_CONCURRENT freed 7723K, 32% free 16891K/24836K, paused 4ms+2ms, total 50ms
,D/dalvikvm( 2664): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836745165867962; DSPS: 11171964; Offset: 1450836404224583783
,I/LocationManagerService(  964): remove 4335bfe8
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2664): GC_CONCURRENT freed 1834K, 32% free 17062K/24836K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2664): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2664): GC_FOR_ALLOC freed 1504K, 31% free 17273K/24836K, paused 20ms, total 20ms
,I/Mlt MonitorService( 2664): parseLastkmsg to dump
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836765166771744; DSPS: 11827354; Offset: 1450836404224572037
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836780034, nextTick: 59986, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836780042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836785169303901; DSPS: 12482797; Offset: 1450836404224571235
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836805170177840; DSPS: 13138186; Offset: 1450836404224560165
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836825171485035; DSPS: 13793588; Offset: 1450836404224585621
,I/GLSUser ( 1546): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1546): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1546): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1546): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1546): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1546): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43317218: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1546): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1546): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1546): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1546): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1546): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1546): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1546): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1546): 	at dalvik.system.NativeStart.run(Native Method)
E/PlayEventLogger( 5110): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5110): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5110): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5110): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5110): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5110): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5110): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5110): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 5110): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5110): isDataSchedulerEnabled():false
D/libc    (  265): _dns_getaddrinfo: iptype =1
,D/libc    (  265): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836840053, nextTick: 59969, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836840059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836845172411494; DSPS: 14448979; Offset: 1450836404224566036
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836865173311638; DSPS: 15104368; Offset: 1450836404224581170
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836885173741504; DSPS: 15759742; Offset: 1450836404224583790
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836900028, nextTick: 59995, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836900054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836905174216429; DSPS: 16415118; Offset: 1450836404224570433
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836925174665337; DSPS: 17070492; Offset: 1450836404224592095
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836945175107371; DSPS: 17725867; Offset: 1450836404224576366
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836960029, nextTick: 59988, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450836960052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836965175582893; DSPS: 18381243; Offset: 1450836404224563606
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450836985176035414; DSPS: 19036617; Offset: 1450836404224588881
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837005176482083; DSPS: 19691992; Offset: 1450836404224577787
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837020037, nextTick: 59978, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837020048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837025178007940; DSPS: 20347402; Offset: 1450836404224577765
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837045178907306; DSPS: 21002792; Offset: 1450836404224561603
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837065179755848; DSPS: 21658180; Offset: 1450836404224555653,
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837080028, nextTick: 59998, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837080050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837085180212238; DSPS: 22313554; Offset: 1450836404224584797
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837105180682272; DSPS: 22968930; Offset: 1450836404224566550
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837125181120381; DSPS: 23624304; Offset: 1450836404224577413
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837140048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837140051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837145182031530; DSPS: 24279694; Offset: 1450836404224573034
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837165182506705; DSPS: 24935069; Offset: 1450836404224590446
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837185182939941; DSPS: 25590444; Offset: 1450836404224565918
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837200031, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837200054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837205183415619; DSPS: 26245819; Offset: 1450836404224583832
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837225183872586; DSPS: 26901194; Offset: 1450836404224583036
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837245184328921; DSPS: 27556569; Offset: 1450836404224581607
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837260039, nextTick: 59979, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837260048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837265185210303; DSPS: 28211958; Offset: 1450836404224577979
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837285185656629; DSPS: 28867333; Offset: 1450836404224566542
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837305186128041; DSPS: 29522708; Offset: 1450836404224580190
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837320037, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837320047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837325186609959; DSPS: 30178084; Offset: 1450836404224573827
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,I/EventLogService( 1846): Aggregate from 1450836527003 (log), 1450835539684 (data)
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837345188187625; DSPS: 30833496; Offset: 1450836404224564579
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837365188621413; DSPS: 31488870; Offset: 1450836404224571121
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837380026, nextTick: 59998, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837380051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837385189572370; DSPS: 32144261; Offset: 1450836404224576033
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837405190025941; DSPS: 32799636; Offset: 1450836404224571840
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837425190458077; DSPS: 33455010; Offset: 1450836404224576730
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837440035, nextTick: 59982, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837440045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837445191382160; DSPS: 34110400; Offset: 1450836404224585285
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837465191828401; DSPS: 34765775; Offset: 1450836404224573763
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837485192268418; DSPS: 35421149; Offset: 1450836404224586534
,D/GCM     ( 1546): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837500035, nextTick: 59981, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837500045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837505193238000; DSPS: 36076541; Offset: 1450836404224579553
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837525193703763; DSPS: 36731917; Offset: 1450836404224557035
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837545194143339; DSPS: 37387291; Offset: 1450836404224569365
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837560039, nextTick: 59977, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837560048, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837565195048644; DSPS: 38042680; Offset: 1450836404224589660
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837585195492247; DSPS: 38698055; Offset: 1450836404224575499
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837605195943527; DSPS: 39353430; Offset: 1450836404224569016
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837620040, nextTick: 59980, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837620049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837625196843954; DSPS: 40008819; Offset: 1450836404224584433
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837645197312904; DSPS: 40664195; Offset: 1450836404224565102
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837665197762788; DSPS: 41319569; Offset: 1450836404224587740
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837680028, nextTick: 59996, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837680055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837685198237833; DSPS: 41974945; Offset: 1450836404224574503
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837705199133930; DSPS: 42630334; Offset: 1450836404224585591
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837725199553938; DSPS: 43285708; Offset: 1450836404224578353
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837740049, nextTick: 59967, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837740059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837745200489986; DSPS: 43941099; Offset: 1450836404224568356
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837765200922834; DSPS: 44596473; Offset: 1450836404224573958
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837785201352170; DSPS: 45251847; Offset: 1450836404224576047
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837800049, nextTick: 59964, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837800060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837805202774436; DSPS: 45907254; Offset: 1450836404224563987
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837825203205900; DSPS: 46562628; Offset: 1450836404224568205
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837845203632652; DSPS: 47218002; Offset: 1450836404224567711
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837860027, nextTick: 60000, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837860051, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837865204522068; DSPS: 47873391; Offset: 1450836404224572117
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837885205478181; DSPS: 48528782; Offset: 1450836404224582185
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837905205918371; DSPS: 49184157; Offset: 1450836404224564612
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837920028, nextTick: 60001, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837920051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837925206819845; DSPS: 49839546; Offset: 1450836404224581076
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837945209303276; DSPS: 50494988; Offset: 1450836404224562066
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837965209727853; DSPS: 51150362; Offset: 1450836404224559396
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837980032, nextTick: 59985, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450837980042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450837985210619965; DSPS: 51805751; Offset: 1450836404224566499
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838005211077774; DSPS: 52461126; Offset: 1450836404224566544
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838025217504845; DSPS: 53116696; Offset: 1450836404224584924
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838040059, nextTick: 59970, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838040060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838045218387059; DSPS: 53772085; Offset: 1450836404224582128
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838065218841532; DSPS: 54427460; Offset: 1450836404224578837
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838085219307749; DSPS: 55082835; Offset: 1450836404224587291
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838100039, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838100045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838105224496974; DSPS: 55738366; Offset: 1450836404224558010
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838125225356834; DSPS: 56393754; Offset: 1450836404224563377
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838145225793367; DSPS: 57049128; Offset: 1450836404224572664
,I/Vold    (  260): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838160035, nextTick: 59996, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838160036, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838165231271691; DSPS: 57704667; Offset: 1450836404224588342,
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838185232178183; DSPS: 58360057; Offset: 1450836404224579307
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838205232612761; DSPS: 59015431; Offset: 1450836404224586638
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  964): Prepared write state in 53ms
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838220080, nextTick: 59951, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838220088, nextTick: 59941, mDrawingTime: 1
,I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2015-12-22-02-22-01.bin
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838225233548512; DSPS: 59670822; Offset: 1450836404224576345
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838245234003950; DSPS: 60326197; Offset: 1450836404224574019
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838265234891641; DSPS: 60981586; Offset: 1450836404224576700
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838280063, nextTick: 59970, mDrawingTime: 0
D/Clock   ( 1140): Clock updated, drawingStartTime : 1450838280064, nextTick: 59969, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838285235341060; DSPS: 61636961; Offset: 1450836404224568355
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838305235830888; DSPS: 62292337; Offset: 1450836404224569902
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1450838325247526104; DSPS: 62948080; Offset: 1450836404224576886
,TIME-OUT KILL (timeout was 1800000ms)
```
