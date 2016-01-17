#### Test 56151093914d164_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
,I/ConfigFetchService( 1857): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1857): launchTask
W/dalvikvm( 1857): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1857): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1857): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1857): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XTTbfYsBa22faxe1x_0oLNQJXjQoMCKhSUix7Vv_lE68aRmkPCKSc71co7Zw4uFETIdD7r3PmzzXFs1Nr3CsFRnF9DZetmVsGLS6jq2lbPyfdRO-rIMtAk4woV9GtBxO5NEn8sZc1kCHoxSUw47pIeeG0GTJuprMY_jvR36Z8k0DI6oOHiUbZlvNRwJh1reyEk0uTQ
I/GoogleURLConnFactory( 1857): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1857): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1857): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1857): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1857): No vision deps
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
--------- beginning of /dev/log/system
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/PeopleContactsSync( 1857): CP2 sync disabled
W/BaseAppContext( 1857): Using Auth Proxy for data requests.
W/BaseAppContext( 1857): Using Auth Proxy for data requests.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/dalvikvm( 1857): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1857): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1857): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1857): Using Auth Proxy for data requests.
W/BaseAppContext( 1857): Using Auth Proxy for data requests.
W/BaseAppContext( 1857): Using Auth Proxy for data requests.
W/BaseAppContext( 1857): Using Auth Proxy for data requests.
W/GAV2    ( 4682): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  964): Killing 3659:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2}
D/AndroidRuntime( 4725): 
D/AndroidRuntime( 4725): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4725): CheckJNI is OFF
D/dalvikvm( 4725): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4725): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4725): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4725): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4725): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1550): GC_EXPLICIT freed 1048K, 29% free 17827K/24832K, paused 1ms+3ms, total 23ms
D/dalvikvm( 4725): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/dalvikvm( 1857): GC_CONCURRENT freed 1527K, 22% free 19464K/24832K, paused 4ms+6ms, total 52ms
D/ChimeraCfgMgr( 1857): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1857): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1857): fetch service done; releasing wakelock
I/ConfigFetchService( 1857): stopping self
E/memtrack( 4725): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4725): failed to load memtrack module: -2
D/AndroidRuntime( 4725): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4725
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (230 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2}
I/Icing   ( 1857): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/dalvikvm(  964): GC_FOR_ALLOC freed 24351K, 54% free 27978K/59812K, paused 175ms, total 175ms
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{43240010 stackId=1, 2 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4725): Shutting down VM
D/UsbSettingsControl( 2629): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2629): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4725): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3830): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4746 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3830): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3830): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4746): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4746): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4746): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Icing   ( 1857): Loaded CLD2 Version V2.0 - 20141016
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.469147 Y: -0.409836 Z: 9.783310 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469147 .y:-0.409836 .z:9.783310
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
V/WebViewChromium( 4746): Binding Chromium to the background looper Looper (main, tid 1) {4286ba20}
I/chromium( 4746): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4746): Initializing chromium process, renderers=0
W/chromium( 4746): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4746): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4746): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4746): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4746): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4746): Remote Branch: 
I/Adreno-EGL( 4746): Local Patches: 
I/Adreno-EGL( 4746): Reconstruct Branch: 
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1857): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/dalvikvm( 4746): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4746): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4746): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4746): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4746): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4746): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4746): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4746): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4746): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4746): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4746): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4746): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4746): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4746): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4746): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4746): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4746): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4746): VFY: replacing opcode 0x6e at 0x0000
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454178 Y: -0.411865 Z: 9.793045 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454178 .y:-0.411865 .z:9.793045
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/SystemWebViewEngine( 4746): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4746): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4746): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4746): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4746): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4746): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4746): Enabling debug mode 0
W/AwContents( 4746): nativeOnDraw failed; clearing to background color.
W/AwContents( 4746): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +304ms
I/ActivityManager( 4746): Timeline: Activity_idle id: android.os.BinderProxy@4286d2e0 time:112801
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/JsMessageQueue( 4746): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4746): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428718e8
D/dalvikvm( 4746): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428718e8
D/jxcore_app_log( 4746): JniHelper::setJavaVM(0x41737838), pthread_self() = 1632733248
D/JX-Cordova( 4746): jxcore cordova android initializing
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3} time:113258
D/ActivityManager(  964): no-history finish of ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{43226788 ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2629): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4746): GC_CONCURRENT freed 2670K, 12% free 21983K/24832K, paused 2ms+2ms, total 32ms
D/dalvikvm( 4746): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/dalvikvm( 4746): GC_FOR_ALLOC freed 327K, 10% free 22356K/24832K, paused 23ms, total 23ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 24.045MB for 42652-byte allocation
D/dalvikvm( 4746): GC_FOR_ALLOC freed 102K, 11% free 22362K/24876K, paused 23ms, total 24ms
D/dalvikvm( 4746): GC_FOR_ALLOC freed 125K, 11% free 22383K/24876K, paused 22ms, total 23ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 24.124MB for 95956-byte allocation
D/dalvikvm( 4746): GC_FOR_ALLOC freed 178K, 11% free 22417K/24972K, paused 23ms, total 23ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 24.203MB for 143930-byte allocation
D/dalvikvm( 4746): GC_FOR_ALLOC freed 251K, 11% free 22464K/25116K, paused 26ms, total 26ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 24.317MB for 215890-byte allocation
D/dalvikvm( 4746): GC_FOR_ALLOC freed 366K, 12% free 22539K/25328K, paused 25ms, total 25ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 24.493MB for 323830-byte allocation
D/dalvikvm( 4746): GC_FOR_ALLOC freed 565K, 12% free 22659K/25648K, paused 23ms, total 23ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 24.764MB for 485740-byte allocation
D/dalvikvm( 4746): GC_FOR_ALLOC freed 858K, 13% free 22835K/26124K, paused 24ms, total 24ms
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4746): GC_FOR_ALLOC freed 1089K, 12% free 23072K/26124K, paused 28ms, total 30ms
D/dalvikvm( 4746): GC_FOR_ALLOC freed 233K, 12% free 23043K/26124K, paused 23ms, total 24ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 25.718MB for 1092904-byte allocation
D/dalvikvm( 4746): GC_CONCURRENT freed 1900K, 14% free 23498K/27192K, paused 1ms+5ms, total 48ms
D/dalvikvm( 4746): WAIT_FOR_CONCURRENT_GC blocked 19ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 26.684MB for 1639352-byte allocation
D/dalvikvm( 4746): GC_CONCURRENT freed 1937K, 17% free 24003K/28796K, paused 2ms+4ms, total 30ms
D/dalvikvm( 4746): GC_FOR_ALLOC freed 1053K, 17% free 23988K/28796K, paused 25ms, total 25ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 27.944MB for 2459024-byte allocation
D/dalvikvm( 4746): GC_CONCURRENT freed 247K, 16% free 26335K/31200K, paused 2ms+2ms, total 28ms
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/dalvikvm( 4746): GC_FOR_ALLOC freed 4227K, 20% free 25028K/31200K, paused 37ms, total 37ms
I/dalvikvm-heap( 4746): Grow heap (frag case) to 30.132MB for 3688532-byte allocation
,D/dalvikvm( 4746): GC_CONCURRENT freed 193K, 18% free 28572K/34804K, paused 2ms+3ms, total 30ms
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4746): GC_FOR_ALLOC freed 4550K, 25% free 26139K/34804K, paused 28ms, total 28ms
,W/jxcore-log( 4746): Initializing JXcore engine
,W/jxcore-log( 4746): JXcore engine is ready
,D/dalvikvm( 4746): GC_CONCURRENT freed 415K, 17% free 28949K/34804K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4746): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/jxcore-log( 4746): Starting JXcore engine
,W/jxcore-log( 4746): Platform android
W/jxcore-log( 4746): 
,W/jxcore-log( 4746): Process ARCH arm
W/jxcore-log( 4746): 
,I/jxcore-log( 4746): JXcore Cordova bridge is ready!
I/jxcore-log( 4746): 
,W/jxcore-log( 4746): JXcore engine is started
,I/chromium( 4746): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4746): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4746): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/jxcore-log( 4746): Toggling radios to true
I/jxcore-log( 4746): 
,D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432498a8:true
,D/BluetoothAdapter( 4746): enable(): BT is already enabled..!
D/WifiService(  964): New client listening to asynchronous messages
,D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DISCONNECT
,I/jxcore-log( 4746): Radios toggled
I/jxcore-log( 4746): 
I/jxcore-log( 4746): My device name is: LGE-LG-D802
I/jxcore-log( 4746): 
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2067): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2067): wlan0: Cancelling scan request
D/wpa_supplicant( 2067): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2067): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2067): TDLS: Tear down peers
,D/wpa_supplicant( 2067): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  964): setWifiEnabled: true pid=4746, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  964): disconnect pid=4746, uid=10304
D/WifiService(  964): reconnect pid=4746, uid=10304
,D/wpa_supplicant( 2067): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2067): wlan0: Deauthentication notification
D/wpa_supplicant( 2067): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2067): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2067): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2067): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2067): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2067): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2067): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2067): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7d50d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2067):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2067): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2067): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2067): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2067): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2067): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2067): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2067): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2067): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2067): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2067): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2067): nl80211: Event message available
D/wpa_supplicant( 2067): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2067): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
W/Settings(  964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2067): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2067): Fast associate: Old scan results
D/wpa_supplicant( 2067): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2067): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2067): wlan0: nl80211: scan request
D/wpa_supplicant( 2067): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2067): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2067): nl80211: Event message available
D/wpa_supplicant( 2067): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2067): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: DisconnectingState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2067): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2067): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2067): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2067): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2067): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
,D/DhcpStateMachine(  964): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
,E/Parcel  (  458): Reading a NULL string not supported here.
D/QCNEA   (  458): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  458): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  458): |CAC| updateNetCfgInfo
V/QCNEA   (  458): |CAC| *********************************************
V/QCNEA   (  458): |CAC|                   Netconfig               
V/QCNEA   (  458): |CAC| *********************************************
V/QCNEA   (  458): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  458): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  458): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  458): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  458): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  458): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  458): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  458): |CAC| *********************************************
D/QCNEA   (  458): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  458): |CAC| net type = 3
V/QCNEA   (  458): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  458): |CAC| Received ssid= NG700
V/QCNEA   (  458): |CAC| 	ssid           =NG700
V/QCNEA   (  458): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  458): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  458): |CAC| *********************************************
D/QCNEA   (  458): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  458): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  458): |CAC| dispatchNetCfg: updating:0xb8bc78dc
,D/QCNEA   (  458): |CAC| readCallback: read len:0, ret:-1, errno:11
D/WifiHS20(  964): hidePasspointNotification off =false
,D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4814 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  270): RouteController
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  270): RouteController
,V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4814): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4814): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4814): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
,V/        (  270): RouteController
,I/PCSuite ( 4814): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  270): RouteController
,V/        (  270): RouteController
,D/PCSuite ( 4814): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4814): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  270): RouteController
,W/NetworkManagementService(  964): route cmd failed: 
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x62894658 clazz=0x6c900001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4851 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 4235:com.google.android.talk/u0a77 (adj 15): empty #17
,V/NativeCrypto( 1550): Read error: ssl=0x63b07b68: I/O error during system call, Connection timed out
,V/NativeCrypto( 1550): SSL shutdown failed: ssl=0x63b07b68: I/O error during system call, Broken pipe
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4851): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4851): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4851): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/QRemote ( 4851): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QRemote ( 4851): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4851): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4851): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4851): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4851): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4851): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4851): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4851): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 3174:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  964): StoppedState
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4682): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1550): onDestroy
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4746): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4746): 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4746): Test app app.js loaded
I/jxcore-log( 4746): 
,I/Choreographer( 4746): Skipped 188 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4746): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4100): onReceive
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/AppUp4:CustFacade( 4100): Context : android.app.ReceiverRestrictedContext@4288a2e0
D/AppUp4:CustFacade( 4100): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4100): isOpenOperator : true
,D/AppUp4:CustFacade( 4100): isPhone : true
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/LicenseContentProvider( 3023): start selecting data
,D/SIMObserver( 3023): simInfo1
,I/AppUp4:EulaManager( 4100): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4100): begin check event
,I/AppUp4:CustModeStarterReceiver( 4100): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4877 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4877): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4877): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4877): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4877): DownloadService onCreate
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4877): in removeSpuriousFiles
,D/eas_req ( 4663): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
D/wpa_supplicant( 2067): nl80211: Event message available
D/wpa_supplicant( 2067): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2067): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2067): wlan0: Event SCAN_RESULTS (3) received
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
D/wpa_supplicant( 2067): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2067): nl80211: Survey data missing
D/wpa_supplicant( 2067): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2067): wlan0: BSS: Add new id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): wlan0: BSS: Add new id 7 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432'
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2067): wlan0: New scan results available
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2067): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2067): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2067): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 2067): WPS: AP 76:04:2b:1b:09:43 type 0 added
D/wpa_supplicant( 2067): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2067): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2067): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2067): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2067): WPS: AP[4] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2067): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2067): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 2067): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2067): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53
D/wpa_supplicant( 2067): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2067): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2067): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2067): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2067): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2067): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2067): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2067): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2067): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2067): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2067): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7d525a8  current_ssid=0x0
D/wpa_supplicant( 2067): scard is not null..
D/wpa_supplicant( 2067): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2067): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2067): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2067): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2067): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2067): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2067): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2067): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2067): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2067): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2067): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2067): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2067): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2067): wlan0: Cancelling scan request
D/wpa_supplicant( 2067): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2067): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2067): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2067): RSN: PMKSA cache search - network_ctx=0xb7d525a8 try_opportunistic=0
D/wpa_supplicant( 2067): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2067): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2067): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2067): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2067): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2067): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2067): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2067): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2067): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2067): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2067): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2067): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2067): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2067): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2067): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2067): nl80211: Unsubscribe mgmt frames handle 0xb7d51590 (mode change)
D/wpa_supplicant( 2067): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2067): nl80211: Register frame type=0xd0 nl_handle=0xb7d51590
D/wpa_supplicant( 2067): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2067): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2067):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067):   * freq=2412
D/wpa_supplicant( 2067):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2067):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2067):   * Auth Type 0
D/wpa_supplicant( 2067):   * WPA Versions 0x2
D/wpa_supplicant( 2067): nl80211: Connect request send successfully
D/wpa_supplicant( 2067): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2067): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 64:7c:34:12:7f:81]
D/wpa_supplicant( 2067): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 64:7c:34:b0:03:6e]
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2067): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2067): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2067): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2067): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
V/DownloadManager( 4877): DownloadService onStartCommand
V/DownloadManager( 4877): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4896 uid=10052 gids={50052, 3003}
V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428b2de8 on behalf of 4877
I/DownloadManager( 4877): in trimDatabase
V/DownloadManager( 4877): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428b45d8 on behalf of 4877
V/DownloadManager( 4877): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/linker  ( 4663): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4663): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4663): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4663): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4663): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4663): register_HtmlEditor, Success
D/HtmlEditor( 4663): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4663): register_HtmlEditorTimer, Success
D/HtmlEditor( 4663): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4663): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4663): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4663): register_HtmlEditorFont, Success
D/HtmlEditor( 4663): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4663): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4663): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4663): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4663): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4663): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4663): JNI_OnLoad Success
I/HubEmail( 4663): JNI_OnLoad()
I/HubEmail( 4663): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4663): registerNatives()
I/HubEmail( 4663): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4663): registerNativeMethods()
I/HubEmail( 4663): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428b63a0 on behalf of 4877
W/Settings( 4663): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4896): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/DownloadManager( 4877): DownloadService onDestroy
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  964): Killing 3984:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4896): [loadRssi] File not exist 
V/LGRssiData( 4896): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4896): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4896): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4896): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4896): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4896): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4896): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/wpa_supplicant( 2067): nl80211: Event message available
D/wpa_supplicant( 2067): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2067): nl80211: Connect event
D/wpa_supplicant( 2067): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2067): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2067): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2067): wlan0: Association info event
D/wpa_supplicant( 2067): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2067): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2067): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2067): wlan0: freq=2412 MHz
D/wpa_supplicant( 2067): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2067): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2067): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2067): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2067): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2067): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): scard is not null..
D/wpa_supplicant( 2067): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2067): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2067): TDLS: Remove peers on association
D/wpa_supplicant( 2067): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2067): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2067): EAPOL: enable timer tick
D/wpa_supplicant( 2067): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2067): wlan0: Setting authentication timeout: 10 sec 0 usec
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2067): wlan0: Cancelling scan request
D/wpa_supplicant( 2067): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2067): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2067): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2067): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2067): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2067): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/wpa_supplicant( 2067): nl80211: if_removed already cleared - ignore event
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/wpa_supplicant( 2067): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2067): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2067): nl80211: if_removed already cleared - ignore event
V/TelephonyAutoProfiling( 4896): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4896): [getValue] FEATURE key : vzw_roaming_state, value : null
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/MobileConnectivityChangeReceiver( 4896): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4896): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4896): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4896): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4917 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  964): Killing 4432:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
D/wpa_supplicant( 2067): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0b 61 96 88 df 86 d9 61 c8 f1 69 52 8a 70 6d ...
D/wpa_supplicant( 2067): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2067): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2067): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2067): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2067): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2067):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2067):   key_nonce - hexdump(len=32): 0b 61 96 88 df 86 d9 61 c8 f1 69 52 8a 70 6d ba bb 1c b8 30 0b aa 18 a9 f8 9a 48 c4 32 75 61 19
D/wpa_supplicant( 2067):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 0b 61 96 88 df 86 d9 61 c8 f1 69 52 8a 70 6d ...
D/wpa_supplicant( 2067): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2067): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2067): Get randomness: len=32 entropy=9
D/wpa_supplicant( 2067): WPA: Renewed SNonce - hexdump(len=32): a5 29 ed 71 a3 c5 6c 16 77 2a 5b e7 73 e9 40 ae 33 70 75 3d d0 5a e4 27 4d c1 79 c0 9f c5 85 08
D/wpa_supplicant( 2067): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): WPA: Nonce1 - hexdump(len=32): a5 29 ed 71 a3 c5 6c 16 77 2a 5b e7 73 e9 40 ae 33 70 75 3d d0 5a e4 27 4d c1 79 c0 9f c5 85 08
D/wpa_supplicant( 2067): WPA: Nonce2 - hexdump(len=32): 0b 61 96 88 df 86 d9 61 c8 f1 69 52 8a 70 6d ba bb 1c b8 30 0b aa 18 a9 f8 9a 48 c4 32 75 61 19
D/wpa_supplicant( 2067): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2067): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2067): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2067): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2067): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2067): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2067): WPA: Derived Key MIC - hexdump(len=16): ec 7c f9 de a9 f5 97 2f 8a 1e 15 4f b1 40 5b 4c
D/wpa_supplicant( 2067): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 a5 29 ed 71 a3 c5 6c 16 77 2a 5b e7 73 e9 40 ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/HyLog   ( 4917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4917): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4917): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2067): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 0,0 00 00 00 00 00 00 02 0b 61 96 88 df 86 d9 61 c8 f1 69 52 8a 70 6d ...
D/wpa_supplicant( 2067): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2067): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2067): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2067): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2067):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2067):   key_nonce - hexdump(len=32): 0b 61 96 88 df 86 d9 61 c8 f1 69 52 8a 70 6d ba bb 1c b8 30 0b aa 18 a9 f8 9a 48 c4 32 75 61 19
D/wpa_supplicant( 2067):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067):   key_rsc - hexdump(len=8): fd 24 00 00 00 00 00 00
D/wpa_supplicant( 2067):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2067):   key_mic - hexdump(len=16): 56 1c 88 c6 4a 1d 51 52 57 31 bd ee 64 c0 be af
D/wpa_supplicant( 2067): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 0b 61 96 88 df 86 d9 61 c8 f1 69 52 8a 70 6d ...
D/wpa_supplicant( 2067): RSN: encrypted key data - hexdump(len=56): c4 3e 17 79 75 e5 43 46 a4 64 03 20 48 20 41 e8 c2 74 68 bf b8 ce 85 dc a1 1b 3d e2 f5 cb b5 91 ...
D/wpa_supplicant( 2067): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2067): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2067): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2067): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 44 4c ...
D/wpa_supplicant( 2067): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2067): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2067): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2067): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2067): WPA: Derived Key MIC - hexdump(len=16): 6a 55 a1 dc db 00 0b b8 ae e0 19 0b 11 9d 0f ab
D/wpa_supplicant( 2067): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2067): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7d51c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2067):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2067): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2067): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2067): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2067): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2067): WPA: RSC - hexdump(len=6): fd 24 00 00 00 00
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ed803a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2067):    broadcast key
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
I/wpa_supplicant( 2067): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63, 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2067): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2067): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2067): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2067): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2067): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2067): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2067): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2067): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2067): EAP: EAP entering state DISABLED
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2067): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2067): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2067): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection established
D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2067): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2067): EAPOL authentication completed successfully
D/wpa_supplicant( 2067): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2067): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2067): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2067): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2067): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  458): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@43208ac0 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@431e93d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-15ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2067): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2067): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4936 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  964): Killing 4572:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4936): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4936): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4936): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LGDMClient( 2903): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2903): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  964): Killing 4621:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4951 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4951): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4951): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4951): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LGDMSGCM( 4951): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4964 uid=10101 gids={50101, 1028, 1015, 3003}
D/wpa_supplicant( 2067): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2067): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2067): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2067): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2067): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2067): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/ActivityManager(  964): Killing 4649:com.lge.bnr/1000 (adj 15): empty #17
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2067): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2067): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring up wlan0
,D/WifiStateMachine(  964): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
,V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43216710 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43216710 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/HyLog   ( 4964): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4964): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4964): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2067): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2067): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2067): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2067): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2067): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  964): handleMessage: X
I/NFS     ( 4964): connectivityManager.getNetworkInfo = TYPE_WIFI
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
E/Parcel  (  458): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/WifiStateMachine(  964): handleMessage: X
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  458): Reading a NULL string not supported here.
,E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
V/WfdStateTracker( 1155): handleWifiStateChangedEvent: 1
D/KeyguardUpdateMonitor( 1141): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  458): Reading a NULL string not supported here.
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/Wireless_Storage( 4964): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4964): intf.getDisplayName() = lo
I/Wireless_Storage( 4964): intf.getDisplayName() = sit0
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/Wireless_Storage( 4964): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4964): intf.getDisplayName() = teql0
I/Wireless_Storage( 4964): intf.getDisplayName() = wlan0
D/NFS     ( 4964): interface name:wlan0 name:wlan0
D/NFS     ( 4964): addr:192.168.1.145 broadcast:192.168.1.255
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): handleMessage: X
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1141): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/dalvikvm(  964): GC_CONCURRENT freed 1216K, 51% free 29645K/59812K, paused 3ms+5ms, total 88ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 69ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 70ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 60ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 54ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 71ms
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4977 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4285:com.android.contacts/u0a21 (adj 15): empty #17
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,D/dalvikvm(  274): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+3ms, total 27ms
,V/        (  270): RouteController
D/HyLog   ( 4977): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4977): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4977): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
V/        (  270): RouteController
V/        (  270): RouteController
V/        (  270): RouteController
,V/        (  270): RouteController
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 26ms
D/QCNEA   (  458): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  458): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  458): |CAC| updateNetCfgInfo
V/QCNEA   (  458): |CAC| *********************************************
V/QCNEA   (  458): |CAC|                   Netconfig               
V/QCNEA   (  458): |CAC| *********************************************
V/QCNEA   (  458): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  458): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  458): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  458): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  458): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  458): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  458): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  458): |CAC| *********************************************
D/QCNEA   (  458): |CAC| Received bssid= c0:ff:d4:d3:aa:48
,D/QCNEA   (  458): |CAC| net type = 1
V/QCNEA   (  458): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  458): |CAC| Received ssid= NG700
V/QCNEA   (  458): |CAC| 	ssid           =NG700
V/QCNEA   (  458): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  458): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  458): |CAC| *********************************************
D/QCNEA   (  458): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  458): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  458): |CAC| dispatchNetCfg: updating:0xb8bc78dc
,D/QCNEA   (  458): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/DhcpStateMachine(  964): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
W/GAV2    ( 4977): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 3ms+3ms, total 26ms
,I/CheckinService( 1857): Checking schedule, now: 1453043012838 next: 1453042954483
,I/CheckinService( 1857): active receiver: enabled
,I/CheckinService( 1857): Preparing to send checkin request
,I/EventLogService( 1857): Accumulating logs since 1453042921322
,I/CheckinRequestBuilder( 1857): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1857): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromium( 4977): Binding Chromium to the main looper Looper (main, tid 1) {428754d8}
,I/chromium( 4977): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4977): Initializing chromium process, renderers=0
,W/chromium( 4977): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4977): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4977): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4977): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4977): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4977): Remote Branch: 
I/Adreno-EGL( 4977): Local Patches: 
I/Adreno-EGL( 4977): Reconstruct Branch: 
,I/NSApplication( 4977): Starting up...
,I/ActivityManager(  964): Killing 4299:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,D/QRemote ( 4851): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4851): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 4851): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4851): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4851): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4851): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4814): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4814): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4851): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4851): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4851): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,I/QRemote ( 4851): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,W/CheckinRequestBuilder( 1857): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43125b68: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5054 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5054): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5054): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5054): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5054): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5054): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 5054): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5054): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5054): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 5054): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5054): install
,I/MultiDex( 5054): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5054): loading existing secondary dex files
,I/MultiDex( 5054): load found 3 secondary dex files
,I/MultiDex( 5054): install done
,D/dalvikvm( 5054): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5054): VFY: unable to resolve instance field 61
,D/dalvikvm( 5054): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5054): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5054): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5054): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 5054): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5054): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5054): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5054): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5054): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5054): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871388
D/dalvikvm( 5054): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871388
,D/dalvikvm( 5054): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871388, skipping init
,D/dalvikvm( 5054): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42871388
D/dalvikvm( 5054): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42871388
,V/JNIHelp ( 5054): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 5054): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871388
,D/dalvikvm( 5054): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42871388
D/dalvikvm( 5054): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42871388
,D/dalvikvm( 5054): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42871388
,I/ProviderInstaller( 5054): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1550): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1550): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1550): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1857): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,D/WearableService( 1738): callingUid 10006, callindPid: 1738
,E/MDM     ( 1423): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1857): Restart initialization of location
I/dalvikvm( 5054): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5054): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5054): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5054): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5054): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5054): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3e000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e3e000
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
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
D/WVCdm   (  276): PrepareKeyRequest: nonce=1880645118
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5054): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a72270
,D/dalvikvm( 5054): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a72270
,D/dalvikvm( 5054): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a72270, skipping init
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2067): EAPOL: startWhen --> 0
D/wpa_supplicant( 2067): EAPOL: disable timer tick
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
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
,D/WVCdm   (  276): PrepareKeyRequest: nonce=722361187
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/WifiStateMachine(  964): handleMessage: X
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,W/Settings( 5054): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 5054): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5083): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/dalvikvm( 5054): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5054): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 64ms
,I/Adreno-EGL( 5054): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5054): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5054): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5054): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5054): Remote Branch: 
I/Adreno-EGL( 5054): Local Patches: 
I/Adreno-EGL( 5054): Reconstruct Branch: 
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Adreno-EGL( 5054): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5054): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5054): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5054): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5054): Remote Branch: 
I/Adreno-EGL( 5054): Local Patches: 
I/Adreno-EGL( 5054): Reconstruct Branch: 
,I/Adreno-EGL( 5054): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5054): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5054): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5054): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5054): Remote Branch: 
I/Adreno-EGL( 5054): Local Patches: 
I/Adreno-EGL( 5054): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1857): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1857): Sending checkin request (11464 bytes)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/CheckinRequestBuilder( 1857): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1857): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1550): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1550): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1550): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1550): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1550): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1550): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x42c7c898: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1857): awaiting user notification for token
,I/CheckinRequestBuilder( 1857): Classify the device as Phone.
,D/GCM     ( 1550): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1550): Message class com.google.f.a.a.p
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinTask( 1857): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1857): Checking schedule, now: 1453043015378 next: 1453620411372
,I/CheckinService( 1857): active receiver: disabled
,D/GCM     ( 1550): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
E/Parcel  (  458): Reading a NULL string not supported here.
,E/Parcel  (  458): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4100): onReceive
D/AppUp4:CustFacade( 4100): Context : android.app.ReceiverRestrictedContext@4288a2e0
D/AppUp4:CustFacade( 4100): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4100): isOpenOperator : true
,D/AppUp4:CustFacade( 4100): isPhone : true
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
I/LicenseContentProvider( 3023): start selecting data
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/SIMObserver( 3023): simInfo1
,I/AppUp4:EulaManager( 4100): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4100): begin check event
,I/AppUp4:CustModeStarterReceiver( 4100): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4100): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4100): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4100): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4100): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4100): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4877): DownloadService onCreate
,I/DownloadManager( 4877): in removeSpuriousFiles
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4663): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4877): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428bc1f8 on behalf of 4877
,I/DownloadManager( 4877): in trimDatabase
V/DownloadManager( 4877): DownloadService onStartCommand
,V/DownloadManager( 4877): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4877): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428bf590 on behalf of 4877
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428bf8f8 on behalf of 4877
I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = false
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/MobileConnectivityChangeReceiver( 4896): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4896): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4663): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4877): DownloadService onDestroy
D/LGDMClient( 2903): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2903): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4951): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/NFS     ( 4964): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4964): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2903): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2903): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2903): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2903): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2903): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4100): onReceive
,D/AppUp4:CustFacade( 4100): Context : android.app.ReceiverRestrictedContext@4288a2e0
D/AppUp4:CustFacade( 4100): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4100): isOpenOperator : true
,D/AppUp4:CustFacade( 4100): isPhone : true
I/LicenseContentProvider( 3023): start selecting data
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/SIMObserver( 3023): simInfo1
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/AppUp4:EulaManager( 4100): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4100): begin check event
,I/AppUp4:CustModeStarterReceiver( 4100): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4877): DownloadService onCreate
,I/DownloadManager( 4877): in removeSpuriousFiles
,V/DownloadManager( 4877): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428c4110 on behalf of 4877
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4877): DownloadService onStartCommand
,I/DownloadManager( 4877): in trimDatabase
V/DownloadManager( 4877): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
V/DownloadManager( 4877): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428c5f48 on behalf of 4877
,V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428c7668 on behalf of 4877
,D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
D/PhoneState( 4387): setPdpRejectCasuse : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/MobileConnectivityChangeReceiver( 4896): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4663): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4896): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4877): DownloadService onDestroy
D/LGDMClient( 2903): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4951): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2903): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2903): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm(  964): GC_EXPLICIT freed 2089K, 51% free 29662K/59812K, paused 3ms+6ms, total 95ms
,E/LGDMClient( 2903): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2903): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2903): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/NFS     ( 4964): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4964): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2903): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4100): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4100): onReceive
,D/AppUp4:CustFacade( 4100): Context : android.app.ReceiverRestrictedContext@4288a2e0
D/AppUp4:CustFacade( 4100): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4100): isOpenOperator : true
,D/AppUp4:CustFacade( 4100): isPhone : true
,I/LicenseContentProvider( 3023): start selecting data
,D/SIMObserver( 3023): simInfo1
,I/AppUp4:EulaManager( 4100): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4100): begin check event
,I/AppUp4:CustModeStarterReceiver( 4100): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4877): DownloadService onCreate
,D/EAS     ( 4663): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4387): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4387): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4387): networkInfo.isConnected() = true
,D/PhoneState( 4387): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4896): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4896): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2903): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4951): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4964): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4964): CONNECT : WIFI_CONNECT
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/LGDMClient( 2903): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 4877): in removeSpuriousFiles
,V/DownloadManager( 4877): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428cbd88 on behalf of 4877
,W/Settings( 4663): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4877): in trimDatabase
V/DownloadManager( 4877): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/LGDMClient( 2903): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428ccfc0 on behalf of 4877
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LGDMClient( 2903): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 4877): DownloadService onStartCommand
,V/DownloadManager( 4877): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
V/DownloadManager( 4877): created cursor android.database.sqlite.SQLiteCursor@428cf8f0 on behalf of 4877
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 2903): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/LGDMClient( 2903): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2903): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4877): DownloadService onDestroy
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5155
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5156
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5164
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5169
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5173
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4977): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
E/Parcel  (  458): Reading a NULL string not supported here.
,E/Parcel  (  458): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.465042 Y: -0.414627 Z: 9.798584 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465042 .y:-0.414627 .z:9.798584
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.470123 Y: -0.413651 Z: 9.808090 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470123 .y:-0.413651 .z:9.808090
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  964): Killing 4682:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
,D/Finsky  ( 4316): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4316): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) },
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5207 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3830): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3830): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
D/HyLog   ( 5207): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5207): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5207): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/MediaCodecList( 5207): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5207): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5207): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5207): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 5207): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5207): MmsConfig.loadMmsSettings
I/Babel   ( 5207): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5207): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5207): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5207): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5207): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5207): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5207): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5207): MmsConfig.loadFromResources
,E/Babel   ( 5207): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5207): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5207): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 5207): [loadRssi] File not exist 
,V/LGRssiData( 5207): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5207): [loadFeatureFromXml] *** start feature loading from xml
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AppUp4:Utils( 4100): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4100): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4100): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/TelephonyAutoProfiling( 5207): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5207): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5207): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/AppUp4:CustModeStarterReceiver( 4100): onReceive
,V/GmsNetworkLocationProvi( 1423): DISABLE
D/AppUp4:CustFacade( 4100): Context : android.app.ReceiverRestrictedContext@4288a2e0
D/AppUp4:CustFacade( 4100): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4100): isOpenOperator : true
,D/AppUp4:CustFacade( 4100): isPhone : true
,I/LicenseContentProvider( 3023): start selecting data
,D/SIMObserver( 3023): simInfo1
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppUp4:EulaManager( 4100): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4100): begin check event
D/AppUp4:Utils( 4100): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4100): Event For Nothing, skip.
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5257 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5257): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5257): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5257): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/ActivityManager(  964): Killing 4814:com.lge.sync/1000 (adj 15): empty #17
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  964): battery changed pluggedType: 2
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/SystemConfig( 5257): BUILD Country: EU
,I/SystemConfig( 5257): BUILD Operator: OPEN
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  964): Killing 4851:com.lge.qremote/u0a96 (adj 15): empty #17
,D/LocationProviderProxy(  964): applying state to connected service
I/SystemConfig( 5257): systemFeature RCS result false
,D/SystemConfig( 5257): refreshRcsSupport() :false
,D/LocationProviderProxy(  964): applying state to connected service
I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5272 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 5272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5272): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 4877:android.process.media/u0a23 (adj 15): empty #17
I/IcingCorporaProvider( 2704): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1857): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1857): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{4467c978 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1857): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1857): GC_CONCURRENT freed 1917K, 22% free 19563K/24832K, paused 2ms+4ms, total 39ms
,I/IcingCorporaProvider( 2704): UpdateCorporaTask done [took 208 ms] updated apps [took 208 ms] 
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/GAV4    ( 5207): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8114 usec
,D/qcom_sensors_hal(  964): hal_acquire_resources
,I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
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
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.466934 Y: -0.420914 Z: 9.801239 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466934 .y:-0.420914 .z:9.801239
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  448): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.486374 Y: -0.410889 Z: 9.782471 
D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  964): current mode = 1  value = 1 1
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.486374 .y:-0.410889 .z:9.782471
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.447556 Y: -0.426407 Z: 9.778046 
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.451996 Y: -0.421982 Z: 9.803574 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.447556 .y:-0.426407 .z:9.778046
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.447220 Y: -0.406296 Z: 9.788147 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447220 .y:-0.406296 .z:9.788147
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.457596 Y: -0.418671 Z: 9.783340 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457596 .y:-0.418671 .z:9.783340
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.456467 Y: -0.420288 Z: 9.787064 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456467 .y:-0.420288 .z:9.787064
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@433c5df8)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
I/WindowManager(  964): No lock screen! windowToken=null
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb82a4450
,D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/WifiStateMachine(  964): handleScreenStateChanged: true
,D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2067): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2067): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2067): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2067): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/SRS_Proc(  276): ParamSet string: screen_state=on
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
,V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433c23c0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,E/SlideAside( 3830): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1828): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:3:51
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3830): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1828): 2 : This is isUpdating : false
D/WeatherAncestor( 1828): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:3:51
D/WeatherService( 1828): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1828): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1828): 2 : shouldTimeTickRegistered : false
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
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.459808 Y: -0.404587 Z: 9.801483 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459808 .y:-0.404587 .z:9.801483
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 384ms
D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.458588 Y: -0.413452 Z: 9.800034 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458588 .y:-0.413452 .z:9.800034
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
D/WifiController(  964): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043031856, nextTick: 8174, mDrawingTime: 2
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043031919, nextTick: 8112, mDrawingTime: 1
,D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
,D/WeatherService( 1828): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:3:51
,D/WeatherService( 1828): 2 : ACTION screen on
,D/WeatherService( 1828): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1828): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:3:51
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  458): Reading a NULL string not supported here.
,E/Parcel  (  458): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.471939 Y: -0.442902 Z: 9.818680 
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454971 Y: -0.408951 Z: 9.790405 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.471939 .y:-0.442902 .z:9.818680
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,D/UsbSettings( 2629): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2629): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2629): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2629): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,I/LGImmersionVibrator(  964): Vibrator off
,D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
,D/WifiStateMachine(  964): processMsg: ConnectedState
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/wpa_supplicant( 2067): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2067): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1155): clear
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{42b1db00 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
D/wpa_supplicant( 2067): wpa_driver_nl80211_driver_cmd  len = 0, 0
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{43240010 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
E/Parcel  (  458): Reading a NULL string not supported here.
,E/Parcel  (  458): Reading a NULL string not supported here.
V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/BubblePopupHelper( 1141): isShowingBubblePopup : false
,D/WeatherService( 1828): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:3:52
D/WeatherService( 1828): 2 : ACTION screen off
,D/WeatherService( 1828): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:3:52
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1448): Emergency Service
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1472): NFC-C OFF
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  448): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,E/ThermalEngine(  291): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043040048, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043040056, nextTick: 59971, mDrawingTime: 2
,I/VacuumService( 1550): Vacuum at: now=1453043040787 tag=VacuumService
,I/GoogleURLConnFactory( 1550): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1550): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1550): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1550): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1550): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1550): No account for auth token provided
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1550): GC_CONCURRENT freed 1816K, 28% free 18041K/24832K, paused 4ms+5ms, total 78ms
,W/Uploader( 1550): No account for auth token provided
,W/Uploader( 1550):  no longer exists, so no auth token.
,W/Uploader( 1550): No account for auth token provided
,W/Uploader( 1550): No account for auth token provided
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043049772984170; DSPS: 5272595; Offset: 1453042888866154337
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043069774865255; DSPS: 5928017; Offset: 1453042888866143332
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043089776631966; DSPS: 6583435; Offset: 1453042888866140023
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043100033, nextTick: 59964, mDrawingTime: 13
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043100057, nextTick: 59971, mDrawingTime: 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043109778232271; DSPS: 7238847; Offset: 1453042888866153414
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043129779879087; DSPS: 7894261; Offset: 1453042888866152281
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043149781676371; DSPS: 8549680; Offset: 1453042888866149028
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043160022, nextTick: 60002, mDrawingTime: 7
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1453043160057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043169783506728; DSPS: 9205100; Offset: 1453042888866148330
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453043189785131251; DSPS: 9860513; Offset: 1453042888866155421
,I/jxcore-log( 4746): --= Surplus to requirements =--
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): ****TEST TOOK:  ms ****
I/jxcore-log( 4746): 
,I/jxcore-log( 4746): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4746): 
,D/AndroidRuntime( 5528): 
D/AndroidRuntime( 5528): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5528): CheckJNI is OFF
,D/dalvikvm( 5528): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5528): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5528): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5528): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5528): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5528): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5528): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5528): failed to load memtrack module: -2
,D/AndroidRuntime( 5528): Calling main entry com.android.commands.pm.Pm
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  964): Killing 4746:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  964):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  964):   Force finishing activity ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  964): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  964): moveHomeStack:
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
,V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  964): resumeTopActivityLocked: Resumed ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43c8c0d8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/WindowState(  964): WIN DEATH: Window{430f99f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  964): Client connection lost with reason: 4
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  964): Skipping PackageSetting{42d4f0e8 com.example.hello/10312} due to missing metadata
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1448): getIsInUseVoLTE : false
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,E/SlideAside( 3830): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,I/SlideAside( 3830): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
,W/GeofencerStateMachine( 1423): Ignoring removeGeofence because network location is disabled.
,W/System.err( 2687): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2687): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
,D/AppUp4:Utils( 4100): [getPackageName] uri : package:com.test.thalitest
W/System.err( 2687): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2687): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
,D/AppUp4  ( 4100): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "sms"
W/System.err( 2687): 	at android.os.Handler.handleCallback(Handler.java:733)
,I/AppUp4  ( 4100):  isExcludedPackage  packagename = com.test.thalitest
,W/System.err( 2687): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 2687): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2687): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2687): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2687): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 2687): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2687): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2687): 	at dalvik.system.NativeStart.main(Native Method)
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/AppUp4  ( 4100):  isExcludedPackage TRUE : com.test.thalitest
I/ActivityManager(  964): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5552 uid=10090 gids={50090}
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "smsto"
,D/dalvikvm( 2704): GC_EXPLICIT freed 4346K, 27% free 18154K/24832K, paused 1ms+4ms, total 99ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 2976K, 50% free 29990K/59076K, paused 2ms+15ms, total 159ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 84ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 83ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 132ms
I/ActivityManager(  964): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5564 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5552): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5552): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5552): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/LockScreenSettings( 5552): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1141): createShortcutInfo...
,D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1141): createShortcutInfo...
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
D/dalvikvm(  964): GC_EXPLICIT freed 483K, 50% free 29934K/59076K, paused 2ms+10ms, total 137ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 218ms
D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 212ms
,D/dalvikvm(  964): WAIT_FOR_CONCURRENT_GC blocked 225ms
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1141): handleShortcutListChanged...
D/AndroidRuntime( 5528): Shutting down VM
,I/ActivityManager(  964): Killing 4663:com.lge.email/u0a24 (adj 15): empty #17
D/dalvikvm( 5528): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 1ms+0ms, total 2ms
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1141): createShortcutInfo...
D/HyLog   ( 5564): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5564): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5564): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1141): handleShortcutListChanged...
I/InputMethodManagerService(  964): IME STATUS OFF
W/Binder  ( 1306): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1306): java.lang.NullPointerException
W/Binder  ( 1306): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1306): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1306): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1306): 	at dalvik.system.NativeStart.run(Native Method)
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
W/InputMethodManagerService(  964): Got RemoteException sending setActive(false) notification to pid 4746 uid 10304
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{42c64b58 u0 com.lge.launcher2/.Launcher t1} time:299233
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/[BNRAppListMgrReceiver]( 5564): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  964): removePackageParticipantsLocked: uid=10304 #1
I/InteractionManagerConfigurator(  964): updateIntentFilterConfig
I/InteractionManagerConfigurator(  964): com.test.thalitest isn't inclued in dragdropPackageList
,I/ActivityManager(  964): Killing 4896:com.google.android.setupwizard/u0a52 (adj 15): empty #17
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/VoicemailCleanupService( 1753): Cleaning up data for package: com.test.thalitest
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5587 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5587): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5587): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5587): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/dalvikvm( 1141): GC_CONCURRENT freed 7805K, 11% free 70604K/78596K, paused 2ms+5ms, total 37ms
,D/dalvikvm( 1141): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 1487): GC_CONCURRENT freed 5556K, 9% free 60780K/66516K, paused 4ms+6ms, total 42ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/LGEmail ( 5587): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5587): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
W/BaseRuntimeLoader( 5587): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5587): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5587): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5587): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/PackageChangeReceiver( 5587): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,D/PackageIntentReceiver( 2629): Not supported Hotkey customization function 
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HideNavigationAppsReceiver( 2629): Receive package name : com.test.thalitest
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/ActivityManager(  964): Killing 4917:com.android.chrome/u0a63 (adj 15): empty #17
,D/HideNavigationAppsReceiver( 2629): Delete mPackageMame : com.test.thalitest
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/IcingCorporaProvider( 2704): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  964): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5611 uid=10073 gids={50073, 3003, 1028, 1015}
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@4286ffb0 time:299532
,E/SQLiteLog( 2687): (2570) os_unix.c:30838: (30) unlink(/mpt/MPT_CommonData.db-journal) - 
,E/SQLiteDatabase( 2687): Error inserting f006=10073 f003=com.google.android.apps.docs f002=1453043192637 f005=5611 f004=13
E/SQLiteDatabase( 2687): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
E/SQLiteDatabase( 2687): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2687): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2687): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2687): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2687): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2687): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2687): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2687): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2687): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2687): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2687): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2687): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2687): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2687): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2687): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)
,D/HyLog   ( 5611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5611): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/SQLiteLog( 2704): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 2704): threadid=15: thread exiting with uncaught exception (group=0x41832e48)
,E/AndroidRuntime( 2704): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2704): Process: com.google.android.googlequicksearchbox:search, PID: 2704
E/AndroidRuntime( 2704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2704): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2704): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/AndroidRuntime( 2704): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2704): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2704): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 2704): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 2704): 	at cau.d(PG:186)
E/AndroidRuntime( 2704): 	at cea.g(PG:591)
E/AndroidRuntime( 2704): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:299)
E/AndroidRuntime( 2704): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 2704): 	at android.content.ContentResolver.update(ContentResolver.java:1332)
E/AndroidRuntime( 2704): 	at ceb.OV(PG:906)
E/AndroidRuntime( 2704): 	at ced.sV(PG:823)
E/AndroidRuntime( 2704): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1267)
E/AndroidRuntime( 2704): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1200)
E/AndroidRuntime( 2704): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2704): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2704): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2704): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2704): Sending signal. PID: 2704 SIG: 9
E/DropBoxManagerService(  964): Can't write: system_app_crash
E/DropBoxManagerService(  964): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  964): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  964): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  964): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  964): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  964): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  964): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  964): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  964): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  964): 	... 5 more
,D/WifiService(  964): Client connection lost with reason: 4
,I/ActivityManager(  964): Process com.google.android.googlequicksearchbox:search (pid 2704) has died.
W/ActivityManager(  964): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
,W/ActivityManager(  964): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cbeff8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 4936:com.lge.drmservice/u0a66 (adj 15): empty #17

```
