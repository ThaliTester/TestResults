#### Test 549702617d40def_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1830): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1830): launchTask
W/dalvikvm( 1830): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1830): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1830): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1830): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WjAE8C37RcoOqGt-GxGcrWZ1M-bmKA0Rz2EiV4nuN9ZjjSLu1YAXRDI6R-iB5ppkXRr3tJA613wBIC8872erUUQGjxbldZ4eyRwjda0FYYvd0Z8JTyzXsZr2lluklG9eVWWUA_jxtCTr-iVDzw9rKqkpa9HmW5s0fQ8x5QNoqN3RyBfTl8haMWK9upSlsYAgFM__WCK3_8Bozupip91I2T2AxsLl0OlcOxot5_NUpHD8UPiro
D/ChimeraCfgMgr( 1830): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1830): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
I/GoogleURLConnFactory( 1830): Using platform SSLCertificateSocketFactory
D/Vision  ( 1830): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1830): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/BaseAppContext( 1830): Using Auth Proxy for data requests.
W/BaseAppContext( 1830): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1830): CP2 sync disabled
W/GAV2    ( 4575): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  963): Killing 4011:com.google.android.gm/u0a68 (adj 15): empty #17
W/BaseAppContext( 1830): Using Auth Proxy for data requests.
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 1 tasks}
W/BaseAppContext( 1830): Using Auth Proxy for data requests.
I/dalvikvm( 1830): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1830): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1830): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1830): Using Auth Proxy for data requests.
W/BaseAppContext( 1830): Using Auth Proxy for data requests.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1532): GC_EXPLICIT freed 1024K, 29% free 17814K/24832K, paused 1ms+4ms, total 29ms
D/AndroidRuntime( 4635): 
D/AndroidRuntime( 4635): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4635): CheckJNI is OFF
I/ConfigFetchService( 1830): fetch service done; releasing wakelock
I/ConfigFetchService( 1830): stopping self
D/dalvikvm( 4635): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4635): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4635): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4635): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4635): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1830): GC_CONCURRENT freed 1543K, 22% free 19466K/24832K, paused 3ms+4ms, total 42ms
D/dalvikvm( 4635): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/ChimeraCfgMgr( 1830): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1830): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1830): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1830): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4635): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4635): failed to load memtrack module: -2
I/Icing   ( 1830): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4635): Calling main entry com.android.commands.am.Am
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4635
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (126 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2}
D/UsbSettingsControl( 2597): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2597): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4635): Shutting down VM
I/SlideAside( 3721): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4635): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  963): startService SlideAside
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{431b0698 stackId=1, 2 tasks}
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3721): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
I/ActivityManager(  963): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4655 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/SlideAside( 3721): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+3ms, total 25ms
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4655): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4655): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4655): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 23ms
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
V/WebViewChromium( 4655): Binding Chromium to the background looper Looper (main, tid 1) {428afd90}
I/chromium( 4655): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4655): Initializing chromium process, renderers=0
W/chromium( 4655): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4655): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4655): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4655): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4655): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4655): Remote Branch: 
I/Adreno-EGL( 4655): Local Patches: 
I/Adreno-EGL( 4655): Reconstruct Branch: 
I/dalvikvm( 4655): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4655): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4655): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4655): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4655): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4655): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4655): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4655): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4655): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4655): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4655): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4655): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4655): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4655): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4655): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4655): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4655): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4655): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4655): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4655): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/BaseRuntimeLoader( 4655): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4655): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4655): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4655): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4655): Enabling debug mode 0
W/AwContents( 4655): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  963): IME STATUS OFF
W/AwContents( 4655): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  963): Displayed com.test.thalitest/.MainActivity: +409ms
I/ActivityManager( 4655): Timeline: Activity_idle id: android.os.BinderProxy@428b1560 time:111434
D/JsMessageQueue( 4655): Set native->JS mode to OnlineEventsBridgeMode
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2037): nl80211: survey data missing!
D/WifiStateMachine(  963): handleMessage: X
D/dalvikvm( 4655): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428b5730
D/dalvikvm( 4655): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428b5730
D/jxcore_app_log( 4655): JniHelper::setJavaVM(0x41772838), pthread_self() = 1639513184
D/JX-Cordova( 4655): jxcore cordova android initializing
I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3} time:111784
D/ActivityManager(  963): no-history finish of ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{42ab9c30 ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2597): [AUTORUN] onStop()
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4655): GC_CONCURRENT freed 2758K, 12% free 21895K/24832K, paused 3ms+3ms, total 60ms
D/dalvikvm( 4655): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/dalvikvm( 4655): WAIT_FOR_CONCURRENT_GC blocked 37ms
D/dalvikvm( 4655): GC_FOR_ALLOC freed 184K, 12% free 21916K/24832K, paused 21ms, total 21ms
D/dalvikvm( 4655): GC_FOR_ALLOC freed 131K, 12% free 21930K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 23.681MB for 95956-byte allocation
D/dalvikvm( 4655): GC_FOR_ALLOC freed 182K, 12% free 21961K/24928K, paused 22ms, total 22ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 23.757MB for 143930-byte allocation
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 4655): GC_FOR_ALLOC freed 253K, 13% free 22009K/25072K, paused 26ms, total 26ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 23.873MB for 215890-byte allocation
D/dalvikvm( 4655): GC_FOR_ALLOC freed 367K, 13% free 22083K/25284K, paused 23ms, total 23ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 24.047MB for 323830-byte allocation
D/dalvikvm( 4655): GC_FOR_ALLOC freed 567K, 14% free 22204K/25604K, paused 24ms, total 24ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 24.320MB for 485740-byte allocation
D/dalvikvm( 4655): GC_FOR_ALLOC freed 863K, 15% free 22379K/26080K, paused 24ms, total 24ms
D/dalvikvm( 4655): GC_FOR_ALLOC freed 1280K, 14% free 22635K/26080K, paused 24ms, total 24ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 25.320MB for 1092904-byte allocation
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.443085 Y: -0.414734 Z: 9.821732 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443085 .y:-0.414734 .z:9.821732
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/dalvikvm( 4655): GC_CONCURRENT freed 1861K, 16% free 23034K/27148K, paused 2ms+5ms, total 46ms
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.436996 Y: -0.423248 Z: 9.809128 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.436996 .y:-0.423248 .z:9.809128
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/dalvikvm( 4655): GC_FOR_ALLOC freed 195K, 16% free 22947K/27148K, paused 23ms, total 24ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 26.146MB for 1639352-byte allocation
D/dalvikvm( 4655): GC_CONCURRENT freed 1633K, 18% free 23609K/28752K, paused 2ms+3ms, total 34ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
D/dalvikvm( 4655): GC_FOR_ALLOC freed 1348K, 18% free 23594K/28752K, paused 26ms, total 27ms
I/dalvikvm-heap( 4655): Grow heap (frag case) to 27.560MB for 2459024-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4655): GC_CONCURRENT freed 1827K, 23% free 24284K/31156K, paused 2ms+2ms, total 38ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 4655): GC_CONCURRENT freed 2355K, 22% free 24536K/31156K, paused 2ms+4ms, total 41ms
,D/dalvikvm( 4655): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4655): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4655): GC_FOR_ALLOC freed 706K, 22% free 24315K/31156K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4655): Grow heap (frag case) to 29.436MB for 3688532-byte allocation
,D/dalvikvm( 4655): GC_CONCURRENT freed 2690K, 27% free 25490K/34760K, paused 1ms+2ms, total 32ms
,D/dalvikvm( 4655): GC_FOR_ALLOC freed 759K, 27% free 25539K/34760K, paused 24ms, total 24ms
,W/jxcore-log( 4655): Initializing JXcore engine
,W/jxcore-log( 4655): JXcore engine is ready
,D/dalvikvm( 4655): GC_CONCURRENT freed 376K, 19% free 28184K/34760K, paused 1ms+1ms, total 27ms
,D/dalvikvm( 4655): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 4655): Starting JXcore engine
,W/jxcore-log( 4655): Platform android
W/jxcore-log( 4655): 
,W/jxcore-log( 4655): Process ARCH arm
W/jxcore-log( 4655): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/jxcore-log( 4655): JXcore Cordova bridge is ready!
I/jxcore-log( 4655): 
,W/jxcore-log( 4655): JXcore engine is started
,I/chromium( 4655): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4655): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4655): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4655): Toggling radios to true
I/jxcore-log( 4655): 
D/BluetoothManagerService(  963): Message: 20
,D/BluetoothManagerService(  963): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c668b8:true
,D/BluetoothAdapter( 4655): enable(): BT is already enabled..!
D/WifiStateMachine(  963): handleMessage: E msg.what=131145
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doBoolean: DISCONNECT
D/WifiService(  963): New client listening to asynchronous messages
D/WifiService(  963): setWifiEnabled: true pid=4655, uid=10304
E/WifiService(  963): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  963): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  963): disconnect pid=4655, uid=10304
,D/WifiService(  963): reconnect pid=4655, uid=10304
I/jxcore-log( 4655): Radios toggled
I/jxcore-log( 4655): 
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2037): TDLS: Tear down peers
D/wpa_supplicant( 2037): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 2037): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2037): wlan0: Deauthentication notification
,D/wpa_supplicant( 2037): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2037): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2037): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2037): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2037): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2037): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb811ad6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2037): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2037): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2037): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2037): nl80211: Ignore disconnect event triggered during reassociation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: ConnectedState
W/Settings(  963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  963): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  963): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131146
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiNative-wlan0(  963): doBoolean: RECONNECT
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2037): Fast associate: Old scan results
D/wpa_supplicant( 2037): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2037): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2037): wlan0: nl80211: scan request
D/wpa_supplicant( 2037): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2037): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147460
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection lost
D/WifiStateMachine(  963): Stopping DHCP and clearing IP
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  963):    returned true
,D/DhcpStateMachine(  963): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  963): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  963): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  963): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  963): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): transitionTo: destState=DisconnectedState
,D/WifiHS20(  963): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
D/QCNEA   (  595): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  595): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  595): |CAC| updateNetCfgInfo
V/QCNEA   (  595): |CAC| *********************************************
V/QCNEA   (  595): |CAC|                   Netconfig               
V/QCNEA   (  595): |CAC| *********************************************
V/QCNEA   (  595): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  595): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  595): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  595): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  595): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  595): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  595): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  595): |CAC| *********************************************
D/QCNEA   (  595): |CAC| Received bssid= 
D/QCNEA   (  595): |CAC| net type = 3
V/QCNEA   (  595): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  595): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  595): |CAC| 	ssid           =NG700
V/QCNEA   (  595): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  595): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  595): |CAC| *********************************************
D/QCNEA   (  595): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  595): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  595): |CAC| dispatchNetCfg: updating:0xb80f08dc
D/QCNEA   (  595): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/QcConnectivityService(  963): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
D/WifiStateMachine(  963): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  963): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4700 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/QcConnectivityService(  963): Attempting to switch to mobile
,D/QcConnectivityService(  963): Attempting to switch to BLUETOOTH_TETHER
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,D/QcConnectivityService(  963): handleConnectivityChange: preConnState=1 connState=2
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
D/HyLog   ( 4700): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4700): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4700): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,I/PCSuite ( 4700): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/PCSuite ( 4700): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4700): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  264): RouteController
,W/NetworkManagementService(  963): route cmd failed: 
W/NetworkManagementService(  963): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  963): '
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  963): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  963): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  963): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  963): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  963): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  963): android_net_utils_resetConnections in env=0x628ccb48 clazz=0x6c400001 iface=wlan0 mask=0x3
D/QcConnectivityService(  963): resetConnections(wlan0, 3)
,I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4729 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  963): Killing 4137:com.google.android.talk/u0a77 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
V/NativeCrypto( 1532): Read error: ssl=0x63a06518: I/O error during system call, Connection timed out
V/NativeCrypto( 1532): SSL shutdown failed: ssl=0x63a06518: I/O error during system call, Broken pipe
,D/HyLog   ( 4729): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4729): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4729): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/QRemote ( 4729): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4729): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4729): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4729): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4729): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4729): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4729): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4729): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4729): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  963): Killing 3111:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,D/DhcpStateMachine(  963): StoppedState
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  963): Skipping unknown process pid 4716
,W/ProcessCpuTracker(  963): Skipping unknown process pid 4719
,I/ActivityManager(  963): Killing 3882:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/GAV2    ( 4575): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/ConfigService( 1532): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3984): onReceive
,D/AppUp4:CustFacade( 3984): Context : android.app.ReceiverRestrictedContext@428c2f70
D/AppUp4:CustFacade( 3984): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3984): isOpenOperator : true
,D/AppUp4:CustFacade( 3984): isPhone : true
,I/LicenseContentProvider( 2967): start selecting data
,D/SIMObserver( 2967): simInfo1
,I/AppUp4:EulaManager( 3984): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3984): begin check event
,I/AppUp4:CustModeStarterReceiver( 3984): Event For GoodConnectivity
,I/ActivityManager(  963): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4776 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4776): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4776): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4776): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4776): DownloadService onCreate
,I/DownloadManager( 4776): in removeSpuriousFiles
,D/EAS     ( 4558): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4558): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4776): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/eas_req ( 4558): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428e7d30 on behalf of 4776
,I/DownloadManager( 4776): in trimDatabase
,V/DownloadManager( 4776): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2037): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2037): nl80211: Received scan results (11 BSSes)
D/wpa_supplicant( 2037): nl80211: Survey data missing
,D/wpa_supplicant( 2037): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 12 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): BSS: last_scan_res_used=11/32 last_scan_full=0
D/wpa_supplicant( 2037): wlan0: New scan results available
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2037): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2037): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 2037): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2037): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2037): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[4] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[5] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2037): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 2037): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2037): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2037): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2037): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2037): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb811c5a8  current_ssid=0x0
D/wpa_supplicant( 2037): scard is not null..
D/wpa_supplicant( 2037): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2037): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2037): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2037): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2037): RSN: PMKSA cache search - network_ctx=0xb811c5a8 try_opportunistic=0
D/wpa_supplicant( 2037): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2037): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2037): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt, 2 proto 2
D/wpa_supplicant( 2037): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2037): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2037): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2037): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2037): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2037): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2037): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2037): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2037): nl80211: Unsubscribe mgmt frames handle 0xb811b590 (mode change)
D/wpa_supplicant( 2037): nl80211: Subscribe to mgmt frames with non-AP handle 0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb811b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2037): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2037):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037):   * freq=2412
D/wpa_supplicant( 2037):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2037):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037):   * Auth Type 0
D/wpa_supplicant( 2037):   * WPA Versions 0x2
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 64:7c:34:38:27:cc]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 10:9a:dd:8e:22:d9]
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  963): handleMessage: E msg.what=147461
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/wpa_supplicant( 2037): nl80211: Connect request send successfully
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  963): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2037): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
W/WifiMonitor(  963): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2037): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428ec1c8 on behalf of 4776
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
V/DownloadManager( 4776): DownloadService onStartCommand
V/DownloadManager( 4776): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428ef540 on behalf of 4776
I/LgeMiscReceiver( 4319): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4319): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4319): networkInfo.isConnected() = false
W/linker  ( 4558): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4558): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4558): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4558): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4558): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4558): register_HtmlEditor, Success
D/HtmlEditor( 4558): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4558): register_HtmlEditorTimer, Success
D/HtmlEditor( 4558): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4558): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4558): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4558): register_HtmlEditorFont, Success
D/HtmlEditor( 4558): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4558): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4558): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4558): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4558): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4558): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4558): JNI_OnLoad Success
I/HubEmail( 4558): JNI_OnLoad()
I/HubEmail( 4558): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4558): registerNatives()
I/HubEmail( 4558): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4558): registerNativeMethods()
I/HubEmail( 4558): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,V/DownloadManager( 4776): DownloadService onDestroy
I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4801 uid=10052 gids={50052, 3003}
D/HyLog   ( 4801): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4801): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4801): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/Settings( 4558): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  963): Killing 4296:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4801): [loadRssi] File not exist 
V/LGRssiData( 4801): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4801): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4801): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4801): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4801): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4801): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4801): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4801): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4801): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4801): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4801): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4801): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4801): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4820 uid=10063 gids={50063, 3003, 1028, 1015}
,D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2037): nl80211: Connect event
D/wpa_supplicant( 2037): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2037): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2037): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2037): wlan0: Association info event
D/wpa_supplicant( 2037): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2037): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2037): wlan0: freq=2412 MHz
D/wpa_supplicant( 2037): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2037): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2037): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2037): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): scard is not null..
D/wpa_supplicant( 2037): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2037): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2037): TDLS: Remove peers on association
D/wpa_supplicant( 2037): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2037): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2037): EAPOL: enable timer tick
D/wpa_supplicant( 2037): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  963): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=CONN,ECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
I/ActivityManager(  963): Killing 4482:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/HyLog   ( 4820): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4820): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4820): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c7 70 76 2f d6 06 b3 29 23 93 d6 eb 30 ca dc ...
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): c7 70 76 2f d6 06 b3 29 23 93 d6 eb 30 ca dc b4 5c ea d5 dd 48 1f 3f a5 b7 ff 7f 81 fc fc 5d 09
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c7 70 76 2f d6 06 b3 29 23 93 d6 eb 30 ca dc ...
D/wpa_supplicant( 2037): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2037): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2037): Get randomness: len=32 entropy=11
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/wpa_supplicant( 2037): WPA: Renewed SNonce - hexdump(len=32): be f2 e7 30 18 da 59 86 63 3b ed 16 26 fa ee 30 cb 55 cb 90 e4 4a 91 77 75 83 6b f6 92 6f 12 0a
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/wpa_supplicant( 2037): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): WPA: Nonce1 - hexdump(len=32): be f2 e7 30 18 da 59 86 63 3b ed 16 26 fa ee 30 cb 55 cb 90 e4 4a 91 77 75 83 6b f6 92 6f 12 0a
D/wpa_supplicant( 2037): WPA: Nonce2 - hexdump(len=32): c7 70 76 2f d6 06 b3 29 23 93 d6 eb 30 ca dc b4 5c ea d5 dd 48 1f 3f a5 b7 ff 7f 81 fc fc 5d 09
D/WifiStateMachine(  963): handleMessage: X
D/wpa_supplicant( 2037): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2037): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): cd 46 79 bb c0 eb 60 7e be e0 57 9f ee e7 b7 50
,D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 be f2 e7 30 18 da 59 86 63 3b ed 16 26 fa ee ...
,D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c7 70 76 2f d6 06 b3 29 23 93 d6 eb 30 ca dc ...
D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): c7 70 76 2f d6 06 b3 29 23 93 d6 eb 30 ca dc b4 5c ea d5 dd 48 1f 3f a5 b7 ff 7f 81 fc fc 5d 09
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): 66 70 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): 30 44 0f 8c 42 0b 76 5d 3f 34 52 5a ec 5f 3d 48
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c7 70 76 2f d6 06 b3 29 23 93 d6 eb 30 ca dc ...
D/wpa_supplicant( 2037): RSN: encrypted key data - hexdump(len=56): 2b 74 94 03 88 27 02 70 16 98 3f 17 9b 35 f6 23 83 35 66 a2 b8 b7 f9 42 02 62 9f ae a6 78 26 8a ...
D/wpa_supplicant( 2037): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2037): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 83 e9 ...
D/wpa_supplicant( 2037): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): 9c 54 71 82 60 6f 92 c0 3b a5 f4 df 28 3b c5 7d
D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2037): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb811bc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2037):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2037): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2037): WPA: RSC - hexdump(len=6): 66 70 00 00 00 00
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6eeb03a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2037):    broadcast key
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2037): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2037): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2037): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2037): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2037): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2037): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2037): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2037): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2037): EAPOL authentication completed successfully
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiMonitor(  963): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  963): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): Network connection established
,D/WifiNative-wlan0(  963): doString: STATUS
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2037): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  963):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  963): ssid=NG700
D/WifiNative-wlan0(  963): id=0
D/WifiNative-wlan0(  963): mode=station
D/WifiNative-wlan0(  963): pairwise_cipher=CCMP
D/WifiNative-wlan0(  963): group_cipher=CCMP
D/WifiNative-wlan0(  963): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  963): wpa_state=COMPLETED
D/WifiNative-wlan0(  963): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  963): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  963): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  963): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4837 uid=10066 gids={50066, 4002, 3003, 1028}
,D/WifiStateMachine(  963): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  963): invokeExitMethods: DisconnectedState
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  963): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  963): invokeEnterMethods: L2ConnectedState
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@43cc88b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/DhcpStateMachine(  963): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
D/DhcpStateMachine(  963): WaitBeforeStartState
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
D/WifiStateMachine(  963): ObtainingIpState{ when=-24ms what=147462 obj=android.net.wifi.StateChangeResult@43cc8fc0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
,D/WifiStateMachine(  963): processMsg: ObtainingIpState
,I/ActivityManager(  963): Killing 4515:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/WifiStateMachine(  963): ObtainingIpState{ when=-24ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-4ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2037): nl80211: survey data missing!
D/WifiStateMachine(  963): handleMessage: X
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  963): handleMessage: E msg.what=196612
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/HyLog   ( 4837): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4837): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4837): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  963): Killing 4543:com.lge.bnr/1000 (adj 15): empty #17
I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4850 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4850): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4850): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4850): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4863 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  963): Killing 4187:com.android.contacts/u0a21 (adj 15): empty #17
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4863): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4863): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  963): doBoolean: SET ps 0
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  963): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  963): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4863): intf.getDisplayName() = lo
I/Wireless_Storage( 4863): intf.getDisplayName() = sit0
I/Wireless_Storage( 4863): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4863): intf.getDisplayName() = teql0
,I/Wireless_Storage( 4863): intf.getDisplayName() = wlan0
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet8
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet2
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet3
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet4
D/WifiStateMachine(  963): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet5
D/CommandListener(  264): Trying to bring up wlan0
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet6
,I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet7
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet0
I/Wireless_Storage( 4863): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet0
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet1
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet2
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet3
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet4
V/LgDhcpStateMachineHelper(  963): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  963): handleMessage: X
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet5
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet6
I/Wireless_Storage( 4863): intf.getDisplayName() = rmnet7
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
I/Wireless_Storage( 4863): CONNECT : WIFI_DISCONNECT
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196613
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/WifiP2pService(  963): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432ced40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432ced40 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): DHCP successful
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  963): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState enter
,D/WifiStateMachine(  963): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4875 uid=10104 gids={50104, 3003, 1028, 1015}
,D/WifiStateMachine(  963): handleMessage: X
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  963): handleMessage: E msg.what=135190
D/WifiStateMachine(  963): processMsg: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  963): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  963): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState enter
,D/WifiStateMachine(  963): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine(  963): handleMessage: X
I/ActivityManager(  963): Killing 4201:com.android.gallery3d/u0a27 (adj 15): empty #17
W/WifiStateTracker(  963): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  963): 
W/WifiStateTracker(  963):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  963):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  963): handleMessage: E msg.what=131092
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  963): processMsg: CaptivePortalCheckState
E/Parcel  (  595): Reading a NULL string not supported here.
,D/WifiStateMachine(  963): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  963): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/WifiStateMachine(  963): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  963): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  963): handleMessage: X
,D/HyLog   ( 4875): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4875): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4875): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=2 connState=1
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/        (  264): RouteController
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,V/        (  264): RouteController
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,W/GAV2    ( 4875): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/QCNEA   (  595): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  595): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  595): |CAC| updateNetCfgInfo
V/QCNEA   (  595): |CAC| *********************************************
V/QCNEA   (  595): |CAC|                   Netconfig               
V/QCNEA   (  595): |CAC| *********************************************
,V/QCNEA   (  595): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  595): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  595): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  595): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  595): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  595): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  595): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  595): |CAC| *********************************************
D/QCNEA   (  595): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  595): |CAC| net type = 1
V/QCNEA   (  595): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  595): |CAC| Received ssid= NG700
V/QCNEA   (  595): |CAC| 	ssid           =NG700
V/QCNEA   (  595): |CAC| 	DNS v4        =192.168.1.1
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  595): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  595): |CAC| *********************************************
D/QCNEA   (  595): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  595): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  595): |CAC| dispatchNetCfg: updating:0xb80f08dc
,D/QCNEA   (  595): |CAC| readCallback: read len:0, ret:-1, errno:11
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,I/CheckinService( 1830): Checking schedule, now: 1451956902144 next: 1451956844475
,I/CheckinService( 1830): active receiver: enabled
,I/CheckinService( 1830): Preparing to send checkin request
,I/EventLogService( 1830): Accumulating logs since 1451956812019
,I/CheckinRequestBuilder( 1830): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1830): Failed to find provider info for com.google.android.wearable.settings
,D/DhcpStateMachine(  963): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  963): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/WebViewChromium( 4875): Binding Chromium to the main looper Looper (main, tid 1) {428ae458}
,I/chromium( 4875): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4875): Initializing chromium process, renderers=0
,D/dalvikvm(  963): GC_EXPLICIT freed 23884K, 49% free 29749K/57996K, paused 4ms+9ms, total 232ms
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,W/chromium( 4875): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/Adreno-EGL( 4875): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4875): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4875): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4875): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4875): Remote Branch: 
I/Adreno-EGL( 4875): Local Patches: 
I/Adreno-EGL( 4875): Reconstruct Branch: 
,I/NSApplication( 4875): Starting up...
,D/QRemote ( 4729): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4729): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4729): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4729): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/QRemote ( 4729): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4729): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4700): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PCSuite ( 4700): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4729): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4729): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4729): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4729): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1830): awaiting user notification for token
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x432ede08: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  963): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4955 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4955): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4955): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4955): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4955): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4955): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4955): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4955): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4955): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4955): install
,I/MultiDex( 4955): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4955): loading existing secondary dex files
,I/MultiDex( 4955): load found 3 secondary dex files
,I/MultiDex( 4955): install done
,D/dalvikvm( 4955): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4955): VFY: unable to resolve instance field 61
,D/dalvikvm( 4955): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4955): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4955): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4955): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4955): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4955): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4955): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4955): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4955): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4955): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b5890
D/dalvikvm( 4955): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b5890
,D/dalvikvm( 4955): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b5890, skipping init
,D/dalvikvm( 4955): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b5890
D/dalvikvm( 4955): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b5890
,V/JNIHelp ( 4955): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4955): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428b5890
,D/dalvikvm( 4955): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428b5890
D/dalvikvm( 4955): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428b5890
,D/dalvikvm( 4955): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428b5890
,I/ProviderInstaller( 4955): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1532): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1532): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1532): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1830): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1771): callingUid 10006, callindPid: 1771
,E/MDM     ( 1422): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DhcpStateMachine(  963): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  963): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  963): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  963): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  963): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  963): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  963): RunningState
I/dalvikvm( 4955): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4955): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4955): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1830): Restart initialization of location
,I/dalvikvm( 4955): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4955): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4955): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  272): Instantiating CDM.
,I/WVCdm   (  272): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  272): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  272): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  272): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d60000
,E/DrmWidevineDash(  272): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d60000
,D/DrmWidevineDash(  272): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  272): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  272): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  272): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  272): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  272): PrepareKeyRequest: nonce=3734963496
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4955): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42acc190
D/dalvikvm( 4955): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42acc190
,D/dalvikvm( 4955): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42acc190, skipping init
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  272): CdmEngine::CloseSession
,D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,D/wpa_supplicant( 2037): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2037): EAPOL: disable timer tick
,I/WVCdm   (  272): CdmEngine::OpenSession
,D/DrmWidevineDash(  272): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  272): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  272): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  272): PrepareKeyRequest: nonce=638245770
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  272): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  963): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/DrmWidevineDash(  272): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  272): CdmEngine::CloseSession
D/DrmWidevineDash(  272): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  272): OEMCrypto_CloseSession returns 0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 4955): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4980): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4955): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4955): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 75ms
,I/Adreno-EGL( 4955): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4955): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4955): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4955): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4955): Remote Branch: 
I/Adreno-EGL( 4955): Local Patches: 
I/Adreno-EGL( 4955): Reconstruct Branch: 
,I/Adreno-EGL( 4955): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4955): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4955): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4955): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4955): Remote Branch: 
I/Adreno-EGL( 4955): Local Patches: 
I/Adreno-EGL( 4955): Reconstruct Branch: 
,W/Settings( 4955): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine(  963): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  963): handleMessage: X
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/QcConnectivityService(  963): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  963):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  963): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,D/GCM     ( 1532): Connected
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GCM     ( 1532): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Adreno-EGL( 4955): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4955): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4955): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4955): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4955): Remote Branch: 
I/Adreno-EGL( 4955): Local Patches: 
I/Adreno-EGL( 4955): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1830): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/CheckinTask( 1830): Sending checkin request (11620 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/CheckinRequestBuilder( 1830): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1830): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/CheckinRequestBuilder( 1830): awaiting user notification for token
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42df9178: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1830): Classify the device as Phone.
,I/CheckinTask( 1830): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1830): Checking schedule, now: 1451956904682 next: 1452534300679
,I/CheckinService( 1830): active receiver: disabled
,I/jxcore-log( 4655): Test app app.js loaded
I/jxcore-log( 4655): 
,I/Choreographer( 4655): Skipped 377 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4655): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/GCM     ( 1532): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3984): onReceive
D/AppUp4:CustFacade( 3984): Context : android.app.ReceiverRestrictedContext@428c2f70
D/AppUp4:CustFacade( 3984): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3984): isOpenOperator : true
,D/AppUp4:CustFacade( 3984): isPhone : true
,I/LicenseContentProvider( 2967): start selecting data
,D/SIMObserver( 2967): simInfo1
,I/AppUp4:EulaManager( 3984): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3984): begin check event
I/AppUp4:CustModeStarterReceiver( 3984): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3984): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3984): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3984): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3984): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3984): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4776): DownloadService onCreate
,I/DownloadManager( 4776): in removeSpuriousFiles
,D/EAS     ( 4558): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4558): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4558): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4776): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428f5c00 on behalf of 4776
,V/DownloadManager( 4776): DownloadService onStartCommand
,V/DownloadManager( 4776): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428f7d70 on behalf of 4776
I/LgeMiscReceiver( 4319): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4319): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4319): networkInfo.isConnected() = false
,V/DownloadManager( 4776): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4801): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4801): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4776): in trimDatabase
,V/DownloadManager( 4776): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428f9930 on behalf of 4776
,D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4850): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
W/Settings( 4558): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NFS     ( 4863): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4863): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2851): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
E/LGDMClient( 2851): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2851): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2851): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2851): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] request level :IDLE....
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/AppUp4:CustModeStarterReceiver( 3984): onReceive
D/AppUp4:CustFacade( 3984): Context : android.app.ReceiverRestrictedContext@428c2f70
D/AppUp4:CustFacade( 3984): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3984): isOpenOperator : true
,D/AppUp4:CustFacade( 3984): isPhone : true
,I/LicenseContentProvider( 2967): start selecting data
,D/SIMObserver( 2967): simInfo1
,I/AppUp4:EulaManager( 3984): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3984): begin check event
,I/AppUp4:CustModeStarterReceiver( 3984): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4776): DownloadService onCreate
,D/EAS     ( 4558): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4558): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4776): in removeSpuriousFiles
,V/DownloadManager( 4776): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428fd588 on behalf of 4776
,I/DownloadManager( 4776): in trimDatabase
V/DownloadManager( 4776): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4319): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4319): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@428fea40 on behalf of 4776
I/LgeMiscReceiver( 4319): networkInfo.isConnected() = true
,D/PhoneState( 4319): setPdpRejectCasuse : false
,W/Settings( 4558): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4801): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4801): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4776): DownloadService onStartCommand
,V/DownloadManager( 4776): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@42900bf0 on behalf of 4776
,D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4776): DownloadService onDestroy
,D/LGDMSGCM( 4850): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2851): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4863): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4863): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2851): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2851): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2851): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2851): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/WifiController(  963): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3984): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3984): onReceive
,D/AppUp4:CustFacade( 3984): Context : android.app.ReceiverRestrictedContext@428c2f70
,D/AppUp4:CustFacade( 3984): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3984): isOpenOperator : true
,D/AppUp4:CustFacade( 3984): isPhone : true
,I/LicenseContentProvider( 2967): start selecting data
,D/SIMObserver( 2967): simInfo1
,I/AppUp4:EulaManager( 3984): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3984): begin check event
,I/AppUp4:CustModeStarterReceiver( 3984): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4558): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4776): DownloadService onCreate
,D/EAS     ( 4558): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4319): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4319): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4319): networkInfo.isConnected() = true
,D/PhoneState( 4319): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4801): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4801): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 4776): in removeSpuriousFiles
,V/DownloadManager( 4776): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@42904d78 on behalf of 4776
I/DownloadManager( 4776): in trimDatabase
V/DownloadManager( 4776): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 2851): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 4558): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@42906420 on behalf of 4776
D/LGDMClient( 2851): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4850): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4776): DownloadService onStartCommand
I/LGDMClient( 2851): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4776): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@42908920 on behalf of 4776
,W/ContextImpl( 4850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2851): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2851): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
I/NFS     ( 4863): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4863): CONNECT : WIFI_CONNECT
D/LGDMClient( 2851): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4776): DownloadService onDestroy
I/LGDMClient( 2851): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV2    ( 4875): Thread[GAThread,5,main]: No campaign data found.
,V/WifiServiceExtension(  963): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/ActivityManager(  963): Killing 4220:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  963): Killing 4575:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  963): battery changed pluggedType: 2
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ActivityManager(  963): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5101 uid=10050 gids={50050, 3003, 1028, 1015}
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+18ms, total 80ms
,D/HyLog   ( 5101): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5101): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5101): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+7ms, total 53ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+1ms, total 24ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/dalvikvm( 5101): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5101): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5101): VFY: replacing opcode 0x6e at 0x000b
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5101): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5101): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5101): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5101): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 5101): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5101): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5101): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5101): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 5101): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5101): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5101): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5101): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 5101): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5101): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5101): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5101): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5101): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5101): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5101): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5101): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 5101): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 5101): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5101): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4776): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4776): created cursor android.database.sqlite.SQLiteCursor@4290dac0 on behalf of 5101
,I/dalvikvm( 5101): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 5101): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5101): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5101): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5101): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5101): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.437286 Y: -0.420944 Z: 9.773361 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437286 .y:-0.420944 .z:9.773361
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.426361 Y: -0.411896 Z: 9.793915 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.426361 .y:-0.411896 .z:9.793915
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  963): GC_EXPLICIT freed 2452K, 49% free 29642K/57996K, paused 4ms+12ms, total 149ms
,D/Finsky  ( 5101): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5101): Total arena pages for JIT: 11
,I/dalvikvm( 5101): Total arena pages for JIT: 12
I/dalvikvm( 5101): Total arena pages for JIT: 13
,I/dalvikvm( 5101): Total arena pages for JIT: 14
,D/Finsky  ( 5101): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5101): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  963): Killing 4700:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 5101): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5101): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5101): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5101): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5101): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1532): GC_EXPLICIT freed 1224K, 29% free 17836K/24832K, paused 1ms+3ms, total 25ms
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5101): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Finsky  ( 5101): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5101): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5101): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5101): [1] DailyHygiene.reschedule: Scheduling new run in 97 minutes (failures=3)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,E/SlideAside( 3721): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  963): Handling package changes for user 0
,I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
,I/ActivityManager(  963): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5188 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/SlideAside( 3721): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5188): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5188): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5188): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5188): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5188): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5188): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5188): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5188): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/Babel   ( 5188): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5188): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5188): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5188): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5188): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5188): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5188): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5188): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5188): MmsConfig.loadFromResources
,E/Babel   ( 5188): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5188): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5188): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/LGRssiData( 5188): [loadRssi] File not exist 
V/LGRssiData( 5188): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5188): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5188): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5188): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5188): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3984): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 3984): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3984): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/AppUp4:CustModeStarterReceiver( 3984): onReceive
,D/AppUp4:CustFacade( 3984): Context : android.app.ReceiverRestrictedContext@428c2f70
D/AppUp4:CustFacade( 3984): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3984): isOpenOperator : true
,D/AppUp4:CustFacade( 3984): isPhone : true
,I/LicenseContentProvider( 2967): start selecting data
,D/SIMObserver( 2967): simInfo1
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppUp4:EulaManager( 3984): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3984): begin check event
D/AppUp4:Utils( 3984): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3984): Event For Nothing, skip.
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5238 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1154): GC_CONCURRENT freed 2903K, 11% free 25447K/28528K, paused 2ms+1ms, total 20ms
,D/HyLog   ( 5238): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5238): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5238): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  963): applying state to connected service
,D/LocationProviderProxy(  963): applying state to connected service
,I/SystemConfig( 5238): BUILD Country: EU
,I/SystemConfig( 5238): BUILD Operator: OPEN
I/SystemConfig( 5238): systemFeature RCS result false
,D/SystemConfig( 5238): refreshRcsSupport() :false
I/ActivityManager(  963): Killing 4729:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5253 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  963): Killing 4558:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
,D/HyLog   ( 5253): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5253): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5253): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,I/IcingCorporaProvider( 2670): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  963): Killing 4801:com.google.android.setupwizard/u0a52 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1830): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1830): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  963): Delaying start of: ServiceRecord{4329b048 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1830): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1830): GC_CONCURRENT freed 1958K, 22% free 19549K/24832K, paused 2ms+3ms, total 36ms
,I/IcingCorporaProvider( 2670): UpdateCorporaTask done [took 220 ms] updated apps [took 220 ms] 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  963): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  963): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  963): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  963): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  963): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/GAV4    ( 5188): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451956920032, nextTick: 59997, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451956920056, nextTick: 59977, mDrawingTime: 0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  963): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  963): [updateScreenState] screen on = false
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  963): _hal_sensors_flush: handle=35
,I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = true
D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6647 usec
,D/qcom_sensors_hal(  963): hal_acquire_resources
,I/qcom_sensors_hal(  963): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  963): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  963): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  963): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  963): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  963): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  963): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.447876 Y: -0.430405 Z: 9.803772 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447876 .y:-0.430405 .z:9.803772
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.440552 Y: -0.415497 Z: 9.809296 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440552 .y:-0.415497 .z:9.809296
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Sensors (  569): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  963): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  963): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  963): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  963): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  963): proximitySensorChanged  positive = true
I/KnockOnPowerController(  963): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.440613 Y: -0.418869 Z: 9.803238 
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.428406 Y: -0.383347 Z: 9.804352 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.440613 .y:-0.418869 .z:9.803238
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.432846 Y: -0.384460 Z: 9.811020 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.432846 .y:-0.384460 .z:9.811020
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.436264 Y: -0.409119 Z: 9.814606 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.436264 .y:-0.409119 .z:9.814606
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.440536 Y: -0.422638 Z: 9.807617 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440536 .y:-0.422638 .z:9.807617
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/KeyguardServiceDelegate(  963): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@447849e8)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb777d450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.447525 Y: -0.415878 Z: 9.782578 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447525 .y:-0.415878 .z:9.782578
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  963): **** SHOWN CALLED ****
I/WindowManager(  963): No lock screen! windowToken=null
,D/WifiStateMachine(  963): handleScreenStateChanged: true
,D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  963): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131127
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=132097
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  963): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2037): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  963): stopMonitoring
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=on, calling pid 963
,V/SRS_Proc(  272): ParamSet string: screen_state=on
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{431c5838 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1759): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 2:22:2
,E/SlideAside( 3721): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3721): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1759): 2 : This is isUpdating : false
,D/WeatherAncestor( 1759): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 2:22:2
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/WeatherService( 1759): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1759): 2 : shouldTimeTickRegistered : false
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1759): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  963): Excessive delay in blankDisplay() while turning screen off: 391ms
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451956922643, nextTick: 57387, mDrawingTime: 2
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.435059 Y: -0.410217 Z: 9.802612 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.435059 .y:-0.410217 .z:9.802612
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451956922718, nextTick: 57315, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.462830 Y: -0.422577 Z: 9.792603 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462830 .y:-0.422577 .z:9.792603
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/WeatherService( 1759): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:22:2
,D/WeatherService( 1759): 2 : ACTION screen on
,D/WeatherService( 1759): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WeatherService( 1759): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:22:2
D/GsmSST  ( 1447): Emergency Service
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_ON
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3}
,D/qcom_sensors_hal(  963): hal_acquire_resources
,D/qcom_sensors_hal(  963): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  963): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  963): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: Rcvd success response from request
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
,I/LGImmersionVibrator(  963): Vibrator off
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/WifiStateMachine(  963): handleScreenStateChanged: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
,D/UsbSettings( 2597): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43a679b0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
V/UsbSettings( 2597): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2597): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2597): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=off, calling pid 963
V/SRS_Proc(  272): ParamSet string: screen_state=off
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  272): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
,D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
D/WifiController(  963): CMD_SCREEN_OFF 
D/WifiController(  963): shouldWifiStayAwake TRUE
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): handleMessage: X
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1154): clear
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{42c04110 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431b0698 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
E/Parcel  (  595): Reading a NULL string not supported here.
,E/Parcel  (  595): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
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
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/dalvikvm(  963): GC_EXPLICIT freed 1903K, 49% free 29796K/57996K, paused 5ms+15ms, total 162ms
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,D/WeatherService( 1759): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:22:3
,D/WeatherService( 1759): 2 : ACTION screen off
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1759): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:22:3
,D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_OFF
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/NfcService( 1472): NFC-C OFF
,I/Sensors (  569): sns_pwr.c(320):releasing wakelock
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1532): Vacuum at: now=1451956931622 tag=VacuumService
,I/GoogleURLConnFactory( 1532): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1532): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1532): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5101): [456] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5101): [1] 5.onFinished: Installation state replication succeeded.
,W/Uploader( 1532): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1532):  no longer exists, so no auth token.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1532): No account for auth token provided
,W/Uploader( 1532): No account for auth token provided
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956940715667346; DSPS: 5271784; Offset: 1451956779833587268
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956960717235516; DSPS: 5927196; Offset: 1451956779833568524
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451956980050, nextTick: 59960, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451956980065, nextTick: 59964, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956980718809622; DSPS: 6582607; Offset: 1451956779833586234
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/wpa_supplicant( 2037): wlan0: BSS: Remove id 9 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 10 BSSID 8e:04:ff:b9:af:27 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 44:e9:dd:10:c0:ac]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 8e:04:ff:b9:af:27]
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957000720481386; DSPS: 7238022; Offset: 1451956779833579531
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957020722046742; DSPS: 7893433; Offset: 1451956779833588491
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957040035, nextTick: 59991, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957040052, nextTick: 59970, mDrawingTime: 4
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957040724256788; DSPS: 8548866; Offset: 1451956779833570753
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957060726113967; DSPS: 9204286; Offset: 1451956779833596878
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957080727441980; DSPS: 9859690; Offset: 1451956779833582117
,D/wpa_supplicant( 2037): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 5 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 6 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 7 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 12 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 4 BSSID 8c:04:ff:b9:af:25 SSID 'SALVADOR' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 38:f8:89:11:e9:11]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:97]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 64:7c:34:12:7f:81]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 64:7c:34:38:27:cc]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 10:9a:dd:8e:22:d9]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 8c:04:ff:b9:af:25]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957100040, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957100046, nextTick: 59985, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957100729320827; DSPS: 10515112; Offset: 1451956779833568874
,D/dalvikvm( 2654): GC_CONCURRENT freed 7778K, 33% free 16865K/24832K, paused 3ms+2ms, total 38ms
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957120731193058; DSPS: 11170533; Offset: 1451956779833579533
,I/LocationManagerService(  963): remove 4334f4a0
,D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2654): GC_CONCURRENT freed 1600K, 31% free 17313K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2654): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/Mlt MonitorService( 2654): parseLastkmsg to dump
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957140733053936; DSPS: 11825954; Offset: 1451956779833578839
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957160048, nextTick: 59966, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957160060, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957160735481794; DSPS: 12481394; Offset: 1451956779833565291
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957180737335536; DSPS: 13136814; Offset: 1451956779833587978
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957200738983393; DSPS: 13792228; Offset: 1451956779833587886
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GLSActivity( 1532): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1532): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1532): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1532): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1532): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1532): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1532): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1532): 	at dalvik.system.NativeStart.run(Native Method)
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42bf09c8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
E/PlayEventLogger( 5101): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5101): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5101): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5101): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5101): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5101): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5101): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5101): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 5101): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5101): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957220026, nextTick: 60002, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957220045, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957220740967916; DSPS: 14447653; Offset: 1451956779833588766
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957240742567283; DSPS: 15103066; Offset: 1451956779833570701
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957260744406912; DSPS: 15758486; Offset: 1451956779833579276
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957280036, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957280055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957280746242060; DSPS: 16413906; Offset: 1451956779833583369
,W/ProcessCpuTracker(  963): Skipping unknown process pid 5744
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957300747773459; DSPS: 17069316; Offset: 1451956779833588889
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957320749277670; DSPS: 17724726; Offset: 1451956779833567221
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957340036, nextTick: 59973, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957340052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957340750899537; DSPS: 18380139; Offset: 1451956779833571657
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957360752538904; DSPS: 19035553; Offset: 1451956779833563074
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957380754140668; DSPS: 19690965; Offset: 1451956779833577924
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957400043, nextTick: 59975, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957400051, nextTick: 59970, mDrawingTime: 4
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957400756082796; DSPS: 20346389; Offset: 1451956779833566927
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957420757952736; DSPS: 21001810; Offset: 1451956779833575295
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957440758831009; DSPS: 21657199; Offset: 1451956779833568558
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957460056, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957460057, nextTick: 59973, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957460760797199; DSPS: 22312623; Offset: 1451956779833581623
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957480762130421; DSPS: 22968027; Offset: 1451956779833572072
,D/dalvikvm( 2654): GC_CONCURRENT freed 2508K, 33% free 16726K/24832K, paused 14ms+3ms, total 67ms
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957500764010674; DSPS: 23623448; Offset: 1451956779833590753
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957520035, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957520041, nextTick: 59987, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957520765910354; DSPS: 24278871; Offset: 1451956779833567825
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957540767375867; DSPS: 24934279; Offset: 1451956779833568494
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957560768962786; DSPS: 25589691; Offset: 1451956779833568499
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957580062, nextTick: 59968, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957580063, nextTick: 59968, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957580770535019; DSPS: 26245102; Offset: 1451956779833584336
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957600771910011; DSPS: 26900507; Offset: 1451956779833586037
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957620774538649; DSPS: 27555953; Offset: 1451956779833590163
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/QcConnectivityService(  963): Setting timer for 720seconds
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957640044, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957640049, nextTick: 59966, mDrawingTime: 6
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957640776418381; DSPS: 28211375; Offset: 1451956779833577805
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957660777990353; DSPS: 28866787; Offset: 1451956779833562863
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957680779600293; DSPS: 29522199; Offset: 1451956779833585889
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957700048, nextTick: 59978, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957700053, nextTick: 59973, mDrawingTime: 3
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957700781197785; DSPS: 30177611; Offset: 1451956779833596467
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957720783047152; DSPS: 30833032; Offset: 1451956779833584262
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957740785315739; DSPS: 31488466; Offset: 1451956779833594548
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957760047, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957760058, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957760787015523; DSPS: 32143882; Offset: 1451956779833585348
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957780788332078; DSPS: 32799286; Offset: 1451956779833559129
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957800790180091; DSPS: 33454706; Offset: 1451956779833576088
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957820055, nextTick: 59968, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957820063, nextTick: 59969, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957820791972687; DSPS: 34110125; Offset: 1451956779833568146
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957840794131326; DSPS: 34765555; Offset: 1451956779833590555
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957860795939548; DSPS: 35420975; Offset: 1451956779833567722
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957880067, nextTick: 59963, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957880068, nextTick: 59965, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957880797983133; DSPS: 36076402; Offset: 1451956779833566630
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957900799349323; DSPS: 36731807; Offset: 1451956779833559529
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957920800960878; DSPS: 37387219; Offset: 1451956779833584170
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957940031, nextTick: 60001, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451957940049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957940802310089; DSPS: 38042623; Offset: 1451956779833590607
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6343
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6345
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957960804752062; DSPS: 38698063; Offset: 1451956779833591174
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451957980806383460; DSPS: 39353477; Offset: 1451956779833574623
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 259 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958000035, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958000055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958000808185952; DSPS: 40008896; Offset: 1451956779833576577
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958020809943757; DSPS: 40664314; Offset: 1451956779833564363
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958040811796561; DSPS: 41319734; Offset: 1451956779833586112
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958060036, nextTick: 59973, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958060051, nextTick: 59976, mDrawingTime: 2,
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958060814197283; DSPS: 41975173; Offset: 1451956779833575946
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958080815779828; DSPS: 42630585; Offset: 1451956779833571577
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958100817442685; DSPS: 43285999; Offset: 1451956779833586484
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958120033, nextTick: 59988, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958120065, nextTick: 59964, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958120819379917; DSPS: 43941423; Offset: 1451956779833570591
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958140821179596; DSPS: 44596842; Offset: 1451956779833569733
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958160822944380; DSPS: 45252260; Offset: 1451956779833564498
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958180045, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958180049, nextTick: 59979, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958180824661144; DSPS: 45907676; Offset: 1451956779833572277
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958200826349001; DSPS: 46563091; Offset: 1451956779833581668
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958220827951962; DSPS: 47218504; Offset: 1451956779833567197
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958240039, nextTick: 59960, mDrawingTime: 13
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958240061, nextTick: 59968, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958240829704767; DSPS: 47873921; Offset: 1451956779833580500
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958260831580436; DSPS: 48529343; Offset: 1451956779833564079
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958280833378345; DSPS: 49184761; Offset: 1451956779833591969
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958300021, nextTick: 59995, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958300071, nextTick: 59958, mDrawingTime: 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958300835045265; DSPS: 49840176; Offset: 1451956779833580422
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958320836702601; DSPS: 50495590; Offset: 1451956779833589809
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958340838516500; DSPS: 51151010; Offset: 1451956779833572653
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/GCM     ( 1532): Message class com.google.f.a.a.i
,D/QcConnectivityService(  963): Setting timer for 720seconds
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/EventLogService( 1830): Aggregate from 1451956902165 (log), 1451956131598 (data)
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958360040, nextTick: 59970, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958360055, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958360840170763; DSPS: 51806424; Offset: 1451956779833578967
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958380841772005; DSPS: 52461837; Offset: 1451956779833562777
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958400844087467; DSPS: 53117273; Offset: 1451956779833558903
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958420036, nextTick: 59966, mDrawingTime: 14
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958420055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958420845751157; DSPS: 53772687; Offset: 1451956779833574644
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958440847434220; DSPS: 54428102; Offset: 1451956779833579240
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958460854492652; DSPS: 55083693; Offset: 1451956779833588111
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958480029, nextTick: 59978, mDrawingTime: 13
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958480060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958480856074050; DSPS: 55739105; Offset: 1451956779833582595
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958500857407845; DSPS: 56394509; Offset: 1451956779833573617
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958520858803045; DSPS: 57049915; Offset: 1451956779833565008
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958540024, nextTick: 59986, mDrawingTime: 12
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958540073, nextTick: 59960, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958540860145485; DSPS: 57705319; Offset: 1451956779833564675
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958560861993915; DSPS: 58360739; Offset: 1451956779833582050
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958580864251304; DSPS: 59016173; Offset: 1451956779833581138
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958600021, nextTick: 60005, mDrawingTime: 6
,I/ProcessStatsService(  963): Prepared write state in 45ms
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958600069, nextTick: 59963, mDrawingTime: 0
,I/ProcessStatsService(  963): Prepared write state in 40ms
,I/ProcessStatsService(  963): Pruning old procstats: /data/system/procstats/state-2016-01-04-06-07-28.bin
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958600865954838; DSPS: 59671589; Offset: 1451956779833575688
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6943
,W/ProcessCpuTracker(  963): Skipping unknown process pid 6945
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1532): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1532): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1532): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1532): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1532): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1532): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1532): GC_CONCURRENT freed 1763K, 28% free 18048K/24832K, paused 9ms+6ms, total 99ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958620867662955; DSPS: 60327005; Offset: 1451956779833574821
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958640869229458; DSPS: 60982416; Offset: 1451956779833584927
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958660034, nextTick: 59969, mDrawingTime: 12
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1451958660052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958660871148357; DSPS: 61637839; Offset: 1451956779833581219
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958680872709546; DSPS: 62293250; Offset: 1451956779833586011
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451958700874433341; DSPS: 62948667; Offset: 1451956779833570304
,TIME-OUT KILL (timeout was 1800000ms)
```
