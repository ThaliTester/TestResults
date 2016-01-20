#### Test 564496606be5677_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1955): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1955): launchTask
,W/dalvikvm( 1955): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1955): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1955): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1955): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1955): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1955): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1955): No vision deps
W/GAV2    ( 4625): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
V/ConfigFetchTask( 1955): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WRKPa71wPLn5wjq4TKG8K7b1l4dzSS92JyJg6f4Af-GgirnZy14QsnnCfzAKB9cf4Ky6qMSTeCPgfYNIqGKDFHZRphZbYUbZc_-L7tdUUxVpp7Dat-1ItBMHyjKjIrS1XLpoKV8un73-8PMmKpOhooxZEG_sL4TM9hJVokL3US26mkYYMmBk5v_ibx_qoxA2eCJkvh
--------- beginning of /dev/log/system
I/ActivityManager(  964): Killing 4082:com.google.android.gm/u0a68 (adj 15): empty #17
I/GoogleURLConnFactory( 1955): Using platform SSLCertificateSocketFactory
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4308cc08 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2}
W/BaseAppContext( 1955): Using Auth Proxy for data requests.
W/BaseAppContext( 1955): Using Auth Proxy for data requests.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PeopleContactsSync( 1955): CP2 sync disabled
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1955): Using Auth Proxy for data requests.
I/dalvikvm( 1955): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1955): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1955): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1955): Using Auth Proxy for data requests.
W/BaseAppContext( 1955): Using Auth Proxy for data requests.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1955): Using Auth Proxy for data requests.
I/Icing   ( 1955): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4672): 
D/AndroidRuntime( 4672): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4672): CheckJNI is OFF
D/dalvikvm( 4672): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4672): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4672): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4672): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4672): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/Icing   ( 1955): Loaded CLD2 Version V2.0 - 20141016
D/dalvikvm( 1955): GC_CONCURRENT freed 1630K, 22% free 19498K/24832K, paused 4ms+6ms, total 51ms
D/dalvikvm( 4672): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.471207 Y: -0.425217 Z: 9.788055 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471207 .y:-0.425217 .z:9.788055
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
I/Icing   ( 1955): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/ChimeraCfgMgr( 1955): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1955): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1955): fetch service done; releasing wakelock
I/ConfigFetchService( 1955): stopping self
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.473984 Y: -0.433548 Z: 9.785004 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473984 .y:-0.433548 .z:9.785004
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
E/memtrack( 4672): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4672): failed to load memtrack module: -2
D/AndroidRuntime( 4672): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4672
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4308cc08 stackId=1, 2 tasks}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (979 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm(  964): GC_FOR_ALLOC freed 490K, 14% free 51599K/59876K, paused 162ms, total 162ms
I/dalvikvm-heap(  964): Grow heap (frag case) to 53.385MB for 856096-byte allocation
D/dalvikvm(  964): GC_FOR_ALLOC freed 35K, 14% free 52403K/60716K, paused 150ms, total 150ms
I/dalvikvm-heap(  964): Grow heap (frag case) to 54.170MB for 856096-byte allocation
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  964): startService SlideAside
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{4308cc08 stackId=1, 2 tasks}
D/AndroidRuntime( 4672): Shutting down VM
D/UsbSettingsControl( 2619): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2619): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4672): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
I/SlideAside( 4055): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4308cc08 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4706 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 4055): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4055): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4706): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4706): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4706): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4706): Binding Chromium to the background looper Looper (main, tid 1) {4281e0f0}
I/chromium( 4706): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4706): Initializing chromium process, renderers=0
I/Adreno-EGL( 4706): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4706): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4706): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4706): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4706): Remote Branch: 
I/Adreno-EGL( 4706): Local Patches: 
I/Adreno-EGL( 4706): Reconstruct Branch: 
W/chromium( 4706): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/dalvikvm( 4706): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4706): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4706): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4706): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4706): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4706): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4706): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4706): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4706): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4706): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4706): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4706): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4706): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4706): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4706): VFY: replacing opcode 0x6e at 0x000d
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/dalvikvm( 4706): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4706): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4706): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4706): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4706): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4706): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4706): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4706): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4706): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4706): Enabling debug mode 0
W/AwContents( 4706): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
W/AwContents( 4706): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +433ms
I/ActivityManager( 4706): Timeline: Activity_idle id: android.os.BinderProxy@4281f9b0 time:113205
D/JsMessageQueue( 4706): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4706): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42823a90
D/dalvikvm( 4706): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42823a90
D/jxcore_app_log( 4706): JniHelper::setJavaVM(0x416e1838), pthread_self() = 1639342760
I/chromium( 4706): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3} time:113517
D/ActivityManager(  964): no-history finish of ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{43250d48 ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2619): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/chromium( 4706): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4706): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 4706): GC_CONCURRENT freed 2642K, 12% free 22010K/24832K, paused 3ms+2ms, total 37ms
D/dalvikvm( 4706): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/dalvikvm( 4706): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4706): GC_FOR_ALLOC freed 410K, 10% free 22356K/24832K, paused 26ms, total 27ms
D/dalvikvm( 4706): GC_FOR_ALLOC freed 104K, 10% free 22363K/24832K, paused 29ms, total 29ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 24.074MB for 63974-byte allocation
D/dalvikvm( 4706): GC_FOR_ALLOC freed 126K, 11% free 22383K/24896K, paused 26ms, total 26ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 24.124MB for 95956-byte allocation
D/dalvikvm( 4706): GC_FOR_ALLOC freed 178K, 11% free 22418K/24992K, paused 23ms, total 24ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 24.204MB for 143930-byte allocation
D/dalvikvm( 4706): GC_FOR_ALLOC freed 253K, 11% free 22465K/25136K, paused 22ms, total 23ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 24.318MB for 215890-byte allocation
W/PluginManager( 4706): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
D/dalvikvm( 4706): GC_FOR_ALLOC freed 367K, 12% free 22539K/25348K, paused 23ms, total 24ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 24.494MB for 323830-byte allocation
D/dalvikvm( 4706): GC_FOR_ALLOC freed 568K, 12% free 22660K/25668K, paused 40ms, total 40ms
D/dalvikvm( 4706): GC_FOR_ALLOC freed 861K, 12% free 22836K/25668K, paused 25ms, total 26ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 25.169MB for 728606-byte allocation
D/dalvikvm( 4706): GC_FOR_ALLOC freed 1279K, 13% free 23092K/26380K, paused 26ms, total 26ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 25.766MB for 1092904-byte allocation
D/dalvikvm( 4706): GC_CONCURRENT freed 1955K, 15% free 23500K/27448K, paused 1ms+5ms, total 59ms
D/dalvikvm( 4706): WAIT_FOR_CONCURRENT_GC blocked 27ms
I/dalvikvm-heap( 4706): Grow heap (frag case) to 26.686MB for 1639352-byte allocation
,D/dalvikvm( 4706): GC_CONCURRENT freed 1961K, 18% free 24004K/29052K, paused 1ms+2ms, total 29ms
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/dalvikvm( 4706): GC_FOR_ALLOC freed 1043K, 18% free 23987K/29052K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4706): Grow heap (frag case) to 27.943MB for 2459024-byte allocation
,D/dalvikvm( 4706): GC_CONCURRENT freed 2007K, 22% free 24747K/31456K, paused 2ms+2ms, total 32ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4706): GC_CONCURRENT freed 2494K, 21% free 25014K/31456K, paused 1ms+8ms, total 63ms
,D/dalvikvm( 4706): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/dalvikvm( 4706): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 4706): GC_FOR_ALLOC freed 65K, 21% free 24951K/31456K, paused 46ms, total 46ms
,I/dalvikvm-heap( 4706): Grow heap (frag case) to 30.057MB for 3688532-byte allocation
,D/dalvikvm( 4706): GC_CONCURRENT freed 485K, 19% free 28448K/35060K, paused 2ms+5ms, total 55ms
,D/dalvikvm( 4706): GC_FOR_ALLOC freed 4200K, 26% free 26123K/35060K, paused 27ms, total 27ms
,W/jxcore-log( 4706): Initializing JXcore engine
,W/jxcore-log( 4706): JXcore engine is ready
,D/dalvikvm( 4706): GC_CONCURRENT freed 403K, 18% free 28939K/35060K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 4706): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 4706): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4706): Starting JXcore engine
,W/jxcore-log( 4706): Platform android
W/jxcore-log( 4706): 
,W/jxcore-log( 4706): Process ARCH arm
W/jxcore-log( 4706): 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4706): JXcore Cordova bridge is ready!
I/jxcore-log( 4706): 
,W/jxcore-log( 4706): JXcore engine is started
,E/jxcore  ( 4706): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4706): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4706): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  964): Finishing activity token=Token{4460c6f0 ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3 f}
,D/dalvikvm(  964): GC_FOR_ALLOC freed 23751K, 52% free 29636K/61556K, paused 127ms, total 127ms
,W/PluginManager( 4706): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 143ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4308cc08 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  964): moveHomeStack:
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  964): resumeTopActivityLocked: Resumed ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  964): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1449): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1818): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:16:11
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1818): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1818): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1818): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1818): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:16:11
,D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,W/IInputConnectionWrapper( 4706): showStatusIcon on inactive InputConnection
I/InputMethodManagerService(  964): IME STATUS OFF
,D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1818): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
D/WeatherService( 1818): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1818): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1818): 2 : Map key string is -2
D/lim     ( 1818): 2 : time = 12:16
I/WeatherReflect( 1818): Model Name : LG-D802
D/WeatherTheme( 1818): 2 : Different view - status_min_formatted : 14 != 16
D/WeatherTheme( 1818): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1818): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1818): 2 : Fixed theme : optimus
D/WeatherTheme( 1818): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1818): 2 : quick cover state : opened : 0
D/Weather.Utils( 1818): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1818): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 6111K, 10% free 71421K/78568K, paused 28ms, total 28ms
,D/dalvikvm( 1487): GC_CONCURRENT freed 5522K, 9% free 60927K/66676K, paused 1ms+2ms, total 29ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/GAV2    ( 4625): Thread[GAThread,5,main]: No campaign data found.
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
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
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 4867K, 9% free 61910K/67376K, paused 17ms, total 17ms
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@4281a4e8 time:116648
,V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/UsbSettings( 2619): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2619): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2619): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2619): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{4328a8c0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1} time:116700
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  964): Killing 4151:com.google.android.talk/u0a77 (adj 15): empty #17
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4706): call to OpenGL ES API with no current context (logged once per thread)
,V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{43a99778 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/ConfigService( 1533): onDestroy
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1487): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,E/ThermalEngine(  289): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.448517 Y: -0.439163 Z: 9.801956 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448517 .y:-0.439163 .z:9.801956
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.451035 Y: -0.427094 Z: 9.803879 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451035 .y:-0.427094 .z:9.803879
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1223): Disconnected process message: 10
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/Finsky  ( 4233): [396] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4233): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2011): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
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
D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6484 usec
D/qcom_sensors_hal(  964): hal_acquire_resources
I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
,D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.458405 Y: -0.408264 Z: 9.801666 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458405 .y:-0.408264 .z:9.801666
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.452118 Y: -0.422684 Z: 9.804352 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452118 .y:-0.422684 .z:9.804352
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  547): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.444595 Y: -0.420517 Z: 9.808838 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444595 .y:-0.420517 .z:9.808838
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.446701 Y: -0.418228 Z: 9.809433 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446701 .y:-0.418228 .z:9.809433
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.456924 Y: -0.417068 Z: 9.810654 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456924 .y:-0.417068 .z:9.810654
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.452454 Y: -0.407974 Z: 9.813797 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452454 .y:-0.407974 .z:9.813797
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43b52e28)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb78ec450
,D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
I/WindowManager(  964): No lock screen! windowToken=null
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.454849 Y: -0.410904 Z: 9.805786 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454849 .y:-0.410904 .z:9.805786
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,E/SlideAside( 4055): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  964): handleScreenStateChanged: true
,D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2011): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  964): stopMonitoring
,D/wpa_supplicant( 2011): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2011): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2011): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  964): handleMessage: X
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/SRS_Proc(  276): ParamSet string: screen_state=on
,D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43358c58 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1818): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:16:33
,I/SlideAside( 4055): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1818): 2 : This is isUpdating : false
,D/WeatherAncestor( 1818): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:16:33
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1818): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1818): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 421ms
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288594091, nextTick: 25942, mDrawingTime: 0
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288594133, nextTick: 25900, mDrawingTime: 0
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:16:34
,D/WeatherService( 1818): 2 : ACTION screen on
D/WeatherService( 1818): 2 : shouldTimeTickRegistered : false
D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
,D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:16:34
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1449): Emergency Service
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1223): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
,I/[LGHome]EVENT( 1487): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1}
,D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  964): Vibrator off
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/[LGHome]EVENT( 1487): [Launcher.java:4955:onStop()]onStop
D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
D/WifiStateMachine(  964): handleScreenStateChanged: false
,D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{42ca0c58 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1154): clear
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
D/KeyguardViewManager( 1140): onScreenTurnedOff()
D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: X
D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1818): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:16:34
D/WeatherService( 1818): 2 : ACTION screen off
D/WeatherService( 1818): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:16:34
D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/NfcService( 1474): NFC-C OFF
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  547): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  289): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288611690921148; DSPS: 5278947; Offset: 1453288450590243658
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288620042, nextTick: 59975, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288620054, nextTick: 59978, mDrawingTime: 0
,I/GoogleURLConnFactory( 1533): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1533): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1533): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1533): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1533): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1533): No account for auth token provided
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Uploader( 1533): No account for auth token provided
,W/Uploader( 1533): No account for auth token provided
,W/Uploader( 1533): No account for auth token provided
,W/Uploader( 1533):  no longer exists, so no auth token.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288631692437495; DSPS: 5934357; Offset: 1453288450590234126
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/rmt_storage(  586): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb83b2178
I/rmt_storage(  586): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  586): wakelock acquired: 1, error no: 42
,I/rmt_storage(  586): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1204084168)
,I/rmt_storage(  586): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
,I/rmt_storage(  586): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  586): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1204084168) wakelock released: 1, error no: 0
I/rmt_storage(  586): 
I/rmt_storage(  586): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb83b2178
,E/Diag_Lib(  685): [IMS_FATAL]| 2912 | 696 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288651693758789; DSPS: 6589760; Offset: 1453288450590243164
,D/wpa_supplicant( 2011): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288671694671230; DSPS: 7245150; Offset: 1453288450590240078
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288680045, nextTick: 59974, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288680054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288691695549139; DSPS: 7900539; Offset: 1453288450590232977
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288711696413506; DSPS: 8555927; Offset: 1453288450590242852
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288731696860060; DSPS: 9211302; Offset: 1453288450590231643
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288740047, nextTick: 59967, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288740059, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288751697745209; DSPS: 9866691; Offset: 1453288450590231782
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288771698631659; DSPS: 10522080; Offset: 1453288450590233222
,D/dalvikvm( 2685): GC_CONCURRENT freed 7890K, 33% free 16761K/24832K, paused 3ms+2ms, total 38ms
,D/dalvikvm( 2685): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x4320bb10: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1533): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1533): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1533): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1533): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1533): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1533): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1533): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4233): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4233): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4233): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4233): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4233): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4233): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4233): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4233): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4233): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4233): isDataSchedulerEnabled():false
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288791699515975; DSPS: 11177469; Offset: 1453288450590232528
,I/LocationManagerService(  964): remove 430999c8
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 1594K, 32% free 17036K/24832K, paused 21ms, total 23ms
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288800025, nextTick: 60003, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288800044, nextTick: 59988, mDrawingTime: 0
,D/dalvikvm( 2685): GC_FOR_ALLOC freed 1603K, 31% free 17224K/24832K, paused 24ms, total 25ms
,I/Mlt MonitorService( 2685): parseLastkmsg to dump
,D/dalvikvm( 2685): GC_CONCURRENT freed 1332K, 28% free 17900K/24832K, paused 8ms+2ms, total 42ms
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288811699952947; DSPS: 11832843; Offset: 1453288450590242254
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288831702320232; DSPS: 12488280; Offset: 1453288450590259686
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288851703661682; DSPS: 13143684; Offset: 1453288450590258362
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288860041, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288860045, nextTick: 59987, mDrawingTime: 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_CONCURRENT freed 2255K, 51% free 30559K/61556K, paused 11ms+10ms, total 158ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288871704102247; DSPS: 13799059; Offset: 1453288450590241164
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288891704548542; DSPS: 14454433; Offset: 1453288450590260212
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288911710399159; DSPS: 15109985; Offset: 1453288450590251454
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288920047, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288920056, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288931711770610; DSPS: 15765390; Offset: 1453288450590249614
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288951713071383; DSPS: 16420793; Offset: 1453288450590238132
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288971713505334; DSPS: 17076167; Offset: 1453288450590244836
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288980041, nextTick: 59988, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453288980044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453288991716422410; DSPS: 17731623; Offset: 1453288450590232225
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289011716850735; DSPS: 18386997; Offset: 1453288450590233304
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289031717739112; DSPS: 19042386; Offset: 1453288450590236671
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289040050, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289040057, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289051718173376; DSPS: 19697760; Offset: 1453288450590243689
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289071719526910; DSPS: 20353164; Offset: 1453288450590254450
,I/ActivityManager(  964): Killing 2165:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289091720481226; DSPS: 21008556; Offset: 1453288450590232203
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289100046, nextTick: 59984, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289100061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289111720926166; DSPS: 21663930; Offset: 1453288450590249897
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289131721811731; DSPS: 22319319; Offset: 1453288450590250452
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289151722714952; DSPS: 22974709; Offset: 1453288450590238146
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289160057, nextTick: 59969, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289160063, nextTick: 59970, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289171723610570; DSPS: 23630098; Offset: 1453288450590248754
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1223): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289191724043687; DSPS: 24285472; Offset: 1453288450590254625
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289211725923940; DSPS: 24940894; Offset: 1453288450590242788
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289220057, nextTick: 59972, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289220062, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289231726814036; DSPS: 25596283; Offset: 1453288450590247874
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289251727250539; DSPS: 26251657; Offset: 1453288450590257131
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289271733740532; DSPS: 26907230; Offset: 1453288450590246880
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289280044, nextTick: 59971, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289280056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289291734712138; DSPS: 27562622; Offset: 1453288450590241924
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289311735153538; DSPS: 28217996; Offset: 1453288450590256078
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289331735605613; DSPS: 28873371; Offset: 1453288450590250389
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289340042, nextTick: 59976, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289340051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289351736567011; DSPS: 29528763; Offset: 1453288450590235224
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289371737426223; DSPS: 30184151; Offset: 1453288450590239944
,D/Finsky  ( 4233): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  964): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  964): Done.
,D/QcConnectivityService(  964): Setting timer for 720seconds
,D/GCM     ( 1533): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4233): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1533): GC_CONCURRENT freed 1757K, 28% free 18073K/24832K, paused 3ms+5ms, total 46ms
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4233): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4233): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4233): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4233): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4233): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2),
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289391737881006; DSPS: 30839526; Offset: 1453288450590236964
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289400054, nextTick: 59968, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289400061, nextTick: 59971, mDrawingTime: 0
,D/Finsky  ( 4233): [396] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4233): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289411738820322; DSPS: 31494917; Offset: 1453288450590230235
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289431742743440; DSPS: 32150405; Offset: 1453288450590247103
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289451743274004; DSPS: 32805782; Offset: 1453288450590258868
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289460032, nextTick: 59986, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289460040, nextTick: 59992, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289471743725612; DSPS: 33461157; Offset: 1453288450590252712
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289491751854198; DSPS: 34116784; Offset: 1453288450590233105
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289511752757107; DSPS: 34772173; Offset: 1453288450590251004
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289520051, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289520064, nextTick: 59968, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289531753633505; DSPS: 35427562; Offset: 1453288450590242392
,D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2011): nl80211: Disconnect event
D/wpa_supplicant( 2011): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2011): wlan0: Deauthentication notification
D/wpa_supplicant( 2011): wlan0:  * reason 0
D/wpa_supplicant( 2011): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2011): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2011): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2011): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2011): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2011): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2011): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2011): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8350d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2011):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2011): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event,
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost
D/WifiStateMachine(  964): Stopping DHCP and clearing IP
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2011): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2011): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2011): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/DhcpStateMachine(  964): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.154/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiHS20(  964): hidePasspointNotification off =false
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 2011): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2011): wlan0: nl80211: scan request
D/wpa_supplicant( 2011): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2011): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2011): wlan0: nl80211: Scan trigger
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
D/QCNEA   (  574): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  574): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  574): |CAC| updateNetCfgInfo
V/QCNEA   (  574): |CAC| *********************************************
V/QCNEA   (  574): |CAC|                   Netconfig               
V/QCNEA   (  574): |CAC| *********************************************
V/QCNEA   (  574): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  574): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  574): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  574): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  574): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  574): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  574): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| Received bssid= 
D/QCNEA   (  574): |CAC| net type = 3
V/QCNEA   (  574): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  574): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  574): |CAC| 	ssid           =NG700
V/QCNEA   (  574): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  574): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  574): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  574): |CAC| dispatchNetCfg: updating:0xb73a28dc
D/QCNEA   (  574): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  964): Attempting to switch to mobile
D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5805 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  270): RouteController
,D/dalvikvm(  274): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 74ms
,V/        (  270): RouteController
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  270): RouteController
,V/        (  270): RouteController
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+4ms, total 28ms
,D/HyLog   ( 5805): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5805): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5805): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,I/PCSuite ( 5805): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  270): RouteController
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 26ms
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x61515ba0 clazz=0x83700001 iface=wlan0 mask=0x3
,D/QcConnectivityService(  964): resetConnections(wlan0, 3)
D/PCSuite ( 5805): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5805): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/DhcpStateMachine(  964): StoppedState
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5849 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  964): Killing 3912:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/NativeCrypto( 1533): Read error: ssl=0x63a77ae8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1533): SSL shutdown failed: ssl=0x63a77ae8: I/O error during system call, Broken pipe
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5849): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5849): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5849): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QRemote ( 5849): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 5849): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 5849): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5849): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5849): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5849): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5849): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5849): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5849): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 4357:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/wpa_supplicant( 2011): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48]
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/SocketClient(  270): write error (Broken pipe)
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2011): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2011): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2011): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2011): nl80211: Survey data missing
D/wpa_supplicant( 2011): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2011): wlan0: BSS: Add new id 4 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: BSS: Add new id 5 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: BSS: Add new id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: BSS: Add new id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2011): wlan0: New scan results available
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2011): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2011): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2011): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2011): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2011): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2011): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2011): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2011): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2011): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2011): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2011): wlan0: 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
D/wpa_supplicant( 2011): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2011): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2011): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2011): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2011): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2011): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2011): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2011): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2011): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2011): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2011): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2011): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2011): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2011): wpa_supp,licant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2011): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2011): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83525a8  current_ssid=0x0
D/wpa_supplicant( 2011): scard is not null..
D/wpa_supplicant( 2011): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2011): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2011): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2011): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2011): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
,D/wpa_supplicant( 2011): wlan0: Cancelling scan request
D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2011): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2011): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2011): RSN: PMKSA cache search - network_ctx=0xb83525a8 try_opportunistic=0,
D/wpa_supplicant( 2011): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2011): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2011): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2011): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2011): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2011): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2011): wlan0: WPA: using KEY_MGMT WPA-PSK
,D/wpa_supplicant( 2011): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2011): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2011): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2011): wlan0: State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2011): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 2011): nl80211: Unsubscribe mgmt frames handle 0xb8351590 (mode change),
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 38:f8:89:11:e9:11]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 06:7c:34:12:7f:81]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
,D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2011): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8351590,
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0a,
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590,
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590,
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590,
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09,
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=1): 06,
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590,
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2011): nl80211: Connect (ifindex=23)
,D/wpa_supplicant( 2011):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2011):   * freq=2412
D/wpa_supplicant( 2011):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2011):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011):   * Auth Type 0
,D/wpa_supplicant( 2011):   * WPA Versions 0x2
D/wpa_supplicant( 2011): nl80211: Connect request send successfully,
D/wpa_supplicant( 2011): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2011): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2011): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2011): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event,
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  964): processMsg: ConnectModeState,
,D/WifiStateMachine(  964): handleMessage: X
,D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2011): nl80211: Connect event
D/wpa_supplicant( 2011): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2011): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2011): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2011): wlan0: Association info event
D/wpa_supplicant( 2011): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2011): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2011): wlan0: freq=2412 MHz
D/wpa_supplicant( 2011): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2011): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2011): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2011): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): scard is not null..
D/wpa_supplicant( 2011): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2011): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2011): TDLS: Remove peers on association
D/wpa_supplicant( 2011): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2011): EAPOL: enable timer tick
D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2011): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2011): wlan0: Cancelling scan request
,D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
,D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2011): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ee e5 0d af 49 bf 74 66 37 13 41 37 18 76 9d ...
D/wpa_supplicant( 2011): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2011): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2011): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2011): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2011): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2011):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2011):   key_nonce - hexdump(len=32): ee e5 0d af 49 bf 74 66 37 13 41 37 18 76 9d bb 95 6a 2d f9 ad ef 61 bf 70 c8 17 f8 b6 0b d9 e3
D/wpa_supplicant( 2011):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ee e5 0d af 49 bf 74 66 37 13 41 37 18 76 9d ...
D/wpa_supplicant( 2011): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2011): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2011): Get randomness: len=32 entropy=5
,D/wpa_supplicant( 2011): WPA: Renewed SNonce - hexdump(len=32): c1 9e e8 99 3f cd 4c ae 3c 5a 26 d3 b0 bc b1 f2 9b 8e 8c 36 b1 e6 39 e4 0e 7d 67 1b af ba 05 1b
D/wpa_supplicant( 2011): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): WPA: Nonce1 - hexdump(len=32): c1 9e e8 99 3f cd 4c ae 3c 5a 26 d3 b0 bc b1 f2 9b 8e 8c 36 b1 e6 39 e4 0e 7d 67 1b af ba 05 1b
D/wpa_supplicant( 2011): WPA: Nonce2 - hexdump(len=32): ee e5 0d af 49 bf 74 66 37 13 41 37 18 76 9d bb 95 6a 2d f9 ad ef 61 bf 70 c8 17 f8 b6 0b d9 e3
D/wpa_supplicant( 2011): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2011): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2011): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2011): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2011): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2011): WPA: Derived Key MIC - hexdump(len=16): 96 b3 b4 fe b6 47 77 94 21 78 2b e5 b3 32 ff f1
,D/wpa_supplicant( 2011): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 c1 9e e8 99 3f cd 4c ae 3c 5a 26 d3 b0 bc b1 ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  964): handleMessage: E msg.what=147462,
,D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2011): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ee e5 0d af 49 bf 74 66 37 13 41 37 18 76 9d ...
D/wpa_supplicant( 2011): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2011): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2011): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2011): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2011):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2011):   key_nonce - hexdump(len=32): ee e5 0d af 49 bf 74 66 37 13 41 37 18 76 9d bb 95 6a 2d f9 ad ef 61 bf 70 c8 17 f8 b6 0b d9 e3
D/wpa_supplicant( 2011):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_rsc - hexdump(len=8): 5e fd 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_mic - hexdump(len=16): bd 61 5b aa 95 a0 99 c6 7d 01 ec 52 61 cd 8e ac
D/wpa_supplicant( 2011): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ee e5 0d af 49 bf 74 66 37 13 41 37 18 76 9d ...
D/wpa_supplicant( 2011): RSN: encrypted key data - hexdump(len=56): fd 1f 75 45 29 c2 e2 b6 bf e6 0f 57 39 4f ba 39 d5 e9 17 12 e3 6b 64 2f 8c 6d 63 9b 85 88 4b cb ...
D/wpa_supplicant( 2011): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2011): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2011): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2011): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 c5 dd ...
D/wpa_supplicant( 2011): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2011): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2011): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2011): WPA: Derived Key MIC - hexdump(len=16): 69 44 d8 46 9a 52 0c 91 87 24 98 77 71 ad fe ad
D/wpa_supplicant( 2011): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2011): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8351c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2011):    addr=c0:ff:d4:d3:aa:48
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/wpa_supplicant( 2011): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2011): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2011): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2011): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2011): WPA: RSC - hexdump(len=6): 5e fd 00 00 00 00
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fb703a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2011):    broadcast key
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2011): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2011): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2011): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2011): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2011): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2011): EAPOL authentication completed successfully
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,D/WifiStateMachine(  964): handleMessage: X
,W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2011): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  964): ssid=NG700
D/WifiNative-wlan0(  964): id=0
D/WifiNative-wlan0(  964): mode=station
D/WifiNative-wlan0(  964): pairwise_cipher=CCMP
D/WifiNative-wlan0(  964): group_cipher=CCMP
D/WifiNative-wlan0(  964): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  964): wpa_state=COMPLETED
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
,D/WifiStateMachine(  964): ObtainingIpState{ when=-26ms what=147462 obj=android.net.wifi.StateChangeResult@433121d0 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): WaitBeforeStartState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
,D/WifiStateMachine(  964): ObtainingIpState{ when=-21ms what=147462 obj=android.net.wifi.StateChangeResult@43044d18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
,D/WifiStateMachine(  964): ObtainingIpState{ when=-21ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=196612
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): processMsg: ObtainingIpState
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  964): ObtainingIpState{ when=-11ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :false
I/AppUp4:CustModeStarterReceiver( 3782): onReceive
D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
D/AppUp4:CustFacade( 3782): isPhone : true
I/LicenseContentProvider( 3054): start selecting data
D/SIMObserver( 3054): simInfo1
I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5888 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5888): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5888): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5888): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2011): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2011): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2011): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  964):    returned null
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432e66f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432e66f8 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Setting iface cfg
D/WifiStateMachine(  964): addressUpdated: 192.168.1.154/24 on wlan0 flags 128 scope 0
D/CommandListener(  270): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-6ms what=131212 obj=192.168.1.154/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-7ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2011): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2011): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2011): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  574): Reading a NULL string not supported here.
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  964): handleMessage: X
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  270): RouteController
,V/DownloadManager( 5888): DownloadService onCreate
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 5888): in removeSpuriousFiles
,D/eas_req ( 4606): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/        (  270): RouteController
,V/DownloadManager( 5888): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@42855f10 on behalf of 5888
,I/DownloadManager( 5888): in trimDatabase
,V/DownloadManager( 5888): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/        (  270): RouteController
V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@428593b8 on behalf of 5888
,V/        (  270): RouteController
,I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5888): DownloadService onStartCommand
V/DownloadManager( 5888): DownloadService onStartCommand
,I/LgeMiscReceiver( 4321): networkInfo.isConnected() = false
,V/        (  270): RouteController
,V/DownloadManager( 5888): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@4285d720 on behalf of 5888
,W/linker  ( 4606): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4606): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4606): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4606): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4606): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4606): register_HtmlEditor, Success
,D/HtmlEditor( 4606): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4606): register_HtmlEditorTimer, Success
D/HtmlEditor( 4606): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4606): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4606): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4606): register_HtmlEditorFont, Success
D/HtmlEditor( 4606): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4606): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4606): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,V/        (  270): RouteController
D/HtmlEditor( 4606): register_HtmlEditorDrawImage, Success
,D/HtmlEditor( 4606): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4606): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4606): JNI_OnLoad Success
,I/HubEmail( 4606): JNI_OnLoad()
I/HubEmail( 4606): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4606): registerNatives()
I/HubEmail( 4606): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4606): registerNativeMethods()
,I/HubEmail( 4606): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,V/        (  270): RouteController
,W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/        (  270): RouteController
,V/DownloadManager( 5888): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5931 uid=10052 gids={50052, 3003}
,V/        (  270): RouteController
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@42861778 on behalf of 5888
,V/DownloadManager( 5888): DownloadService onDestroy
D/QCNEA   (  574): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  574): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  574): |CAC| updateNetCfgInfo
V/QCNEA   (  574): |CAC| *********************************************
V/QCNEA   (  574): |CAC|                   Netconfig               
V/QCNEA   (  574): |CAC| *********************************************
V/QCNEA   (  574): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  574): |CAC| 	NetConfig: subtype rl =21
,V/QCNEA   (  574): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  574): |CAC| 	NetConfig: ip4        =192.168.1.154
V/QCNEA   (  574): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  574): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  574): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  574): |CAC| net type = 1
V/QCNEA   (  574): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
,D/QCNEA   (  574): |CAC| Received ssid= NG700
V/QCNEA   (  574): |CAC| 	ssid           =NG700
V/QCNEA   (  574): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  574): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  574): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  574): |CAC| dispatchNetCfg: updating:0xb73a28dc
,D/QCNEA   (  574): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  964): Killing 4525:com.android.defcontainer/u0a4 (adj 15): empty #17
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/HyLog   ( 5931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5931): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DhcpStateMachine(  964): DHCP request on wlan0
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5931): [loadRssi] File not exist 
,V/LGRssiData( 5931): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5931): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 5931): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5931): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5931): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5931): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 5931): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5931): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 5931): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5931): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5931): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5958 uid=10063 gids={50063, 3003, 1028, 1015}
,E/PhoneMonitor( 5931): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5931): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  964): Killing 4566:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1955): Checking schedule, now: 1453289546293 next: 1453288515938
,I/CheckinService( 1955): active receiver: enabled
,D/HyLog   ( 5958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1955): Preparing to send checkin request
D/HyLog   ( 5958): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/EventLogService( 1955): Accumulating logs since 1453288483405
,I/CheckinRequestBuilder( 1955): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1955): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5973 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 5973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5973): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5973): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Killing 4593:com.lge.bnr/1000 (adj 15): empty #17
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5987 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 5987): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5987): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5987): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6001 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 4200:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6001): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6001): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 6001): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/dalvikvm(  964): GC_EXPLICIT freed 1983K, 50% free 30694K/60792K, paused 6ms+13ms, total 197ms
,I/Wireless_Storage( 6001): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6001): intf.getDisplayName() = lo
I/Wireless_Storage( 6001): intf.getDisplayName() = sit0
I/Wireless_Storage( 6001): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6001): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6001): intf.getDisplayName() = wlan0
D/NFS     ( 6001): interface name:wlan0 name:wlan0
D/NFS     ( 6001): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
,D/NFS     ( 6001): interface name:wlan0 name:wlan0
D/NFS     ( 6001): addr:192.168.1.154 broadcast:192.168.1.255
,I/Wireless_Storage( 6001): CONNECT : WIFI_CONNECT
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6014 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4216:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6014): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6014): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6014): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 6014): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/wpa_supplicant( 2011): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2011): EAPOL: disable timer tick
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1955): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43041ea8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6032 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6032): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6032): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6032): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/dalvikvm( 6032): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6032): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6032): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6032): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6032): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6032): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6032): install
,I/MultiDex( 6032): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6032): loading existing secondary dex files
,I/MultiDex( 6032): load found 3 secondary dex files
,I/MultiDex( 6032): install done
,V/WebViewChromium( 6014): Binding Chromium to the main looper Looper (main, tid 1) {4281c430}
,I/chromium( 6014): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6014): Initializing chromium process, renderers=0
,D/dalvikvm( 6032): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6032): VFY: unable to resolve instance field 61
,D/dalvikvm( 6032): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6032): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6032): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6032): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6032): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6032): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6032): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6032): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6032): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6032): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42823680
D/dalvikvm( 6032): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42823680
,D/dalvikvm( 6032): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42823680, skipping init
,W/chromium( 6014): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/dalvikvm( 6032): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42823680
D/dalvikvm( 6032): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42823680
,V/JNIHelp ( 6032): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Adreno-EGL( 6014): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6014): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6014): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6014): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6014): Remote Branch: 
I/Adreno-EGL( 6014): Local Patches: 
I/Adreno-EGL( 6014): Reconstruct Branch: 
,I/NSApplication( 6014): Starting up...
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  964): Killing 4625:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/dalvikvm( 6032): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42823680
,D/dalvikvm( 6032): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42823680
D/dalvikvm( 6032): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42823680
,D/dalvikvm( 6032): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42823680
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/QRemote ( 5849): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5849): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5849): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5849): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 5849): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5849): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5805): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5805): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5849): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5849): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5849): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5849): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ProviderInstaller( 6032): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1533): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1533): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1533): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1955): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1745): callingUid 10006, callindPid: 1745
,E/MDM     ( 1424): [61] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1955): Restart initialization of location
,I/dalvikvm( 6032): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 6032): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6032): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6032): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6032): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6032): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e09000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e09000
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
D/WVCdm   (  276): PrepareKeyRequest: nonce=2543609432
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6032): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a3c938
D/dalvikvm( 6032): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a3c938
,D/dalvikvm( 6032): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a3c938, skipping init
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,W/Settings( 6032): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  964): handleMessage: X
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6032): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6093): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 6032): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6032): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 95ms
,I/Adreno-EGL( 6032): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6032): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6032): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6032): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6032): Remote Branch: 
I/Adreno-EGL( 6032): Local Patches: 
I/Adreno-EGL( 6032): Reconstruct Branch: 
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1,
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=4292724808
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 6032): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6032): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6032): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6032): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6032): Remote Branch: 
I/Adreno-EGL( 6032): Local Patches: 
I/Adreno-EGL( 6032): Reconstruct Branch: 
,I/Adreno-EGL( 6032): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6032): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6032): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6032): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6032): Remote Branch: 
I/Adreno-EGL( 6032): Local Patches: 
I/Adreno-EGL( 6032): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1955): Classify the device as Phone.
,V/NativeCrypto( 1955): SSL shutdown failed: ssl=0x6c6ecbc8: I/O error during system call, Connection timed out
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3782): onReceive
,D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
,D/AppUp4:CustFacade( 3782): isPhone : true
,I/LicenseContentProvider( 3054): start selecting data
,D/SIMObserver( 3054): simInfo1
,I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
,I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3782): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3782): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3782): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3782): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3782): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 5888): DownloadService onCreate
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4606): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 5888): in removeSpuriousFiles
,V/DownloadManager( 5888): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@428663f0 on behalf of 5888
,V/DownloadManager( 5888): DownloadService onStartCommand
,V/DownloadManager( 5888): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4321): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 5931): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5931): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5888): in trimDatabase
,V/DownloadManager( 5888): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@42869070 on behalf of 5888
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@42869680 on behalf of 5888
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5888): DownloadService onDestroy
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LGDMSGCM( 5987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 6001): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6001): CONNECT : WIFI_CONNECT
,W/ContextImpl( 5987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.154
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3782): onReceive
D/DhcpStateMachine(  964): RunningState
D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
,D/AppUp4:CustFacade( 3782): isPhone : true
,I/LicenseContentProvider( 3054): start selecting data
,D/SIMObserver( 3054): simInfo1
,I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
,I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5888): DownloadService onCreate
,I/DownloadManager( 5888): in removeSpuriousFiles
V/DownloadManager( 5888): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@4286d8b8 on behalf of 5888
,I/DownloadManager( 5888): in trimDatabase
,V/DownloadManager( 5888): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@4286ef60 on behalf of 5888
,V/DownloadManager( 5888): DownloadService onStartCommand
,V/DownloadManager( 5888): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@42871460 on behalf of 5888
I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4321): networkInfo.isConnected() = true
,D/PhoneState( 4321): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5931): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5931): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5888): DownloadService onDestroy
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 5987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 6001): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6001): CONNECT : WIFI_CONNECT
E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinTask( 1955): Sending checkin request (11467 bytes)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/EventLogService( 1955): Aggregate from 1453289546330 (log), 1453287665419 (data)
,I/CheckinRequestBuilder( 1955): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1955): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1955): awaiting user notification for token
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x42c68a50: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1955): Classify the device as Phone.
,D/GCM     ( 1533): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1533): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/CheckinTask( 1955): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1955): Checking schedule, now: 1453289550866 next: 1453866946862
,I/CheckinService( 1955): active receiver: disabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] request level :IDLE....
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/AppUp4:CustModeStarterReceiver( 3782): onReceive
D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
D/AppUp4:CustFacade( 3782): isPhone : true
I/LicenseContentProvider( 3054): start selecting data
D/SIMObserver( 3054): simInfo1
I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 5888): DownloadService onCreate
,D/EAS     ( 4606): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4606): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 5888): in removeSpuriousFiles
,V/DownloadManager( 5888): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm( 1955): GC_CONCURRENT freed 1971K, 22% free 19575K/24832K, paused 5ms+6ms, total 110ms
,D/dalvikvm( 1955): WAIT_FOR_CONCURRENT_GC blocked 22ms
,V/DownloadManager( 5888): DownloadService onStartCommand
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@42875ae8 on behalf of 5888
,V/DownloadManager( 5888): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4321): networkInfo.isConnected() = true
D/PhoneState( 4321): setPdpRejectCasuse : false
V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@428780c0 on behalf of 5888
I/DownloadManager( 5888): in trimDatabase
,V/DownloadManager( 5888): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5888): created cursor android.database.sqlite.SQLiteCursor@428790e0 on behalf of 5888
D/MobileConnectivityChangeReceiver( 5931): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5931): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5888): DownloadService onDestroy
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 1955): Checking schedule, now: 1453289550976 next: 1453866946862
,I/CheckinService( 1955): active receiver: disabled
,D/LGDMSGCM( 5987): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
W/ContextImpl( 5987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6001): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6001): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1533): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289551754805685; DSPS: 36082960; Offset: 1453288450590254904
,I/GAV2    ( 6014): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  964): Killing 5805:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): Killing 4233:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6210 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms",
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "smsto"
,E/SlideAside( 4055): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4055): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  964): Handling package changes for user 0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
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
,D/dalvikvm(  964): GC_EXPLICIT freed 2786K, 50% free 30795K/60792K, paused 7ms+16ms, total 214ms
,D/HyLog   ( 6210): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6210): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6210): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Babel   ( 6210): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6210): MmsConfig.loadMmsSettings
,I/MediaCodecList( 6210): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6210): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6210): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6210): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 6210): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6210): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 6210): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6210): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6210): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6210): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 6210): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6210): MmsConfig.loadFromResources
,E/Babel   ( 6210): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6210): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 6210): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6210): [loadRssi] File not exist 
,V/LGRssiData( 6210): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6210): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 3782): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3782): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3782): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3782): onReceive
,V/TelephonyAutoProfiling( 6210): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
D/AppUp4:CustFacade( 3782): isPhone : true
V/TelephonyAutoProfiling( 6210): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6210): [getValue] FEATURE key : vzw_roaming_state, value : null
I/LicenseContentProvider( 3054): start selecting data
,D/SIMObserver( 3054): simInfo1
,I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
D/AppUp4:Utils( 3782): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3782): Event For Nothing, skip.
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6258 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6258): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6258): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6258): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+4ms, total 33ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 26ms
,I/SystemConfig( 6258): BUILD Country: EU
,I/SystemConfig( 6258): BUILD Operator: OPEN
I/ActivityManager(  964): Killing 5849:com.lge.qremote/u0a96 (adj 15): empty #17
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 26ms
,I/SystemConfig( 6258): systemFeature RCS result false
,D/SystemConfig( 6258): refreshRcsSupport() :false
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6276 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 5888:android.process.media/u0a23 (adj 15): empty #17
,D/HyLog   ( 6276): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6276): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6276): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 4606:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2697): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6292 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6292): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6292): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6292): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6292): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6292): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6292): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6292): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6292): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6292): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6292): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6292): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6292): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6292): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6292): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6292): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/IcingCorporaProvider( 2697): UpdateCorporaTask done [took 325 ms] updated apps [took 325 ms] 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings( 6292): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6292): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6292): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6292): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6292): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6292): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 6292): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6292): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6292): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6292): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6292): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 6292): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6292): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6292): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  964): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6329 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 6329): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6329): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6329): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6292): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6292): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6292): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6292): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6292): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1955): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1955): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1955): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6329): DownloadService onCreate
,I/DownloadManager( 6329): in removeSpuriousFiles
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@4285bd38 on behalf of 6329
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@4285b9d8 on behalf of 6292
V/DownloadManager( 6329): DownloadService onStartCommand
,I/DownloadManager( 6329): in trimDatabase
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6329): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@4285fe28 on behalf of 6329
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@42861260 on behalf of 6329
,D/Finsky  ( 6292): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 6329): DownloadService onDestroy
,D/Finsky  ( 6292): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  964): Killing 5931:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6292): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6292): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6292): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6292): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm( 1533): GC_EXPLICIT freed 1161K, 28% free 18005K/24832K, paused 9ms+6ms, total 57ms
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Finsky  ( 6292): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6292): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 6292): Total arena pages for JIT: 11
,I/dalvikvm( 6292): Total arena pages for JIT: 12
I/dalvikvm( 6292): Total arena pages for JIT: 13
,I/dalvikvm( 6292): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm(  964): GC_EXPLICIT freed 1219K, 50% free 30639K/60792K, paused 4ms+12ms, total 155ms
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6292): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6292): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6292): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6292): [1] DailyHygiene.reschedule: Scheduling new run in 88 minutes (failures=3)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6210): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  964): Killing 5958:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289571755264793; DSPS: 36738335; Offset: 1453288450590256249
,D/Finsky  ( 6292): [462] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6292): [1] 5.onFinished: Installation state replication succeeded.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289580055, nextTick: 59967, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289580062, nextTick: 59971, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289591760392024; DSPS: 37393863; Offset: 1453288450590256526
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289611761254725; DSPS: 38049252; Offset: 1453288450590234218
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289631761720759; DSPS: 38704627; Offset: 1453288450590242488
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289640048, nextTick: 59971, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289640057, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289651762171481; DSPS: 39360002; Offset: 1453288450590235446
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289671766178712; DSPS: 40015493; Offset: 1453288450590244875
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289691767517507; DSPS: 40670897; Offset: 1453288450590240896
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289700041, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289700055, nextTick: 59977, mDrawingTime: 0
,D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2011): nl80211: Disconnect event
D/wpa_supplicant( 2011): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2011): wlan0: Deauthentication notification
D/wpa_supplicant( 2011): wlan0:  * reason 0
D/wpa_supplicant( 2011): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2011): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2011): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2011): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2011): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2011): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2011): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2011): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  964): handleMessage: E msg.what=147460
D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState,
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): Network connection lost,
D/WifiStateMachine(  964): Stopping DHCP and clearing IP,
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1,
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8350d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2011):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2011): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2011): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2011): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2011): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2011): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2011): wlan0: nl80211: scan request
D/wpa_supplicant( 2011): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/wpa_supplicant( 2011): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2011): wlan0: nl80211: Scan trigger
,D/WifiNative-wlan0(  964):    returned true
,D/DhcpStateMachine(  964): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  964): addressRemoved: 192.168.1.154/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  964): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,D/WifiHS20(  964): hidePasspointNotification off =false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
D/QCNEA   (  574): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  574): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  574): |CAC| updateNetCfgInfo
V/QCNEA   (  574): |CAC| *********************************************
V/QCNEA   (  574): |CAC|                   Netconfig               
V/QCNEA   (  574): |CAC| *********************************************
V/QCNEA   (  574): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  574): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  574): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  574): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  574): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  574): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  574): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| Received bssid= 
D/QCNEA   (  574): |CAC| net type = 3
V/QCNEA   (  574): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  574): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  574): |CAC| 	ssid           =NG700
V/QCNEA   (  574): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  574): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  574): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  574): |CAC| dispatchNetCfg: updating:0xb73a28dc
D/QCNEA   (  574): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  964): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/QcConnectivityService(  964): Attempting to switch to mobile
,D/QcConnectivityService(  964): Attempting to switch to BLUETOOTH_TETHER
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=1 connState=2
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  964): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6520 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131213
D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  964): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  270): RouteController
,D/HyLog   ( 6520): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6520): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6520): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,I/PCSuite ( 6520): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6520): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6520): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  270): RouteController
W/NetworkManagementService(  964): route cmd failed: 
W/NetworkManagementService(  964): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  964): android_net_utils_resetConnections in env=0x61515ba0 clazz=0xcae00001 iface=wlan0 mask=0x3
D/QcConnectivityService(  964): resetConnections(wlan0, 3)
,I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6565 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,V/NativeCrypto( 1533): Read error: ssl=0x63b99f80: I/O error during system call, Connection timed out
,V/NativeCrypto( 1533): SSL shutdown failed: ssl=0x63b99f80: I/O error during system call, Broken pipe
I/ActivityManager(  964): Killing 5973:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/HyLog   ( 6565): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6565): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6565): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/DhcpStateMachine(  964): StoppedState
,D/QRemote ( 6565): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/QRemote ( 6565): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/QRemote ( 6565): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,D/GpsLocationProvider(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/QRemote ( 6565): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6565): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6565): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6565): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/LocSvc_java(  964): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 6565): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6565): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  964): Killing 5987:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2011): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2011): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2011): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2011): nl80211: Survey data missing
D/wpa_supplicant( 2011): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2011): wlan0: BSS: Add new id 8 BSSID 00:26:f2:18:08:c8 SSID 'm.m.netgear'
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2011): wlan0: New scan results available
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2011): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2011): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2011): WPS: AP[1] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2011): wlan0: Selecting BSS from priority group 1,
,D/wpa_supplicant( 2011): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-44 wps
D/wpa_supplicant( 2011): wlan0:    skip - blacklisted (count=1 limit=0)
,D/wpa_supplicant( 2011): wlan0: 1: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps,
D/wpa_supplicant( 2011): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2011): wlan0: 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 caps=0x411 level=-77
,D/wpa_supplicant( 2011): wlan0:    skip - SSID mismatch,
D/wpa_supplicant( 2011): wlan0: 3: 00:26:f2:18:08:c8 ssid='m.m.netgear' wpa_ie_len=24 rsn_ie_len=0 caps=0x411 level=-89
D/wpa_supplicant( 2011): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 2011): wlan0: No APs found - clear blacklist and try again,
D/wpa_supplicant( 2011): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2011): wlan0: Selecting BSS from priority group 1
,D/wpa_supplicant( 2011): wlan0: 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-44 wps,
,D/wpa_supplicant( 2011): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2011): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700',
,D/wpa_supplicant( 2011): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2011): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
,D/wpa_supplicant( 2011): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2011): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2011): wpa_supplicant_check_mdm_ac_policy policy: 0,
,D/wpa_supplicant( 2011): wlan0: [MDM] lg mdm allow/disallow auto connect is not set ,
,D/wpa_supplicant( 2011): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83525a8  current_ssid=0x0,
,D/wpa_supplicant( 2011): scard is not null..
,D/wpa_supplicant( 2011): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
,D/wpa_supplicant( 2011): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 2011): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30,
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01,
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00,
,D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2011): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2011): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2011): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2011): wlan0: Cancelling scan request
,D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2011): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2011): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2011): RSN: PMKSA cache search - network_ctx=0xb83525a8 try_opportunistic=0
D/wpa_supplicant( 2011): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2011): wlan0: RSN: using IEEE 802.11i/D9.0
,D/wpa_supplicant( 2011): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2011): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2011): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): wlan0: WPA: using GTK CCMP,
D/wpa_supplicant( 2011): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2011): wlan0: WPA: using KEY_MGMT WPA-PSK,
D/wpa_supplicant( 2011): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2011): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2011): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2011): wlan0: State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2011): nl80211: Set mode ifindex 23 iftype 2 (STATION),
D/wpa_supplicant( 2011): nl80211: Unsubscribe mgmt frames handle 0xb8351590 (mode change),
D/wpa_supplicant( 2011): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
,D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590,
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0d
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:26:f2:18:08:c8],
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
,D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 04 0e,
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2011): nl80211: Register frame type=0xd0 nl_handle=0xb8351590,
D/wpa_supplicant( 2011): nl80211: Register frame match - hexdump(len=2): 0a 11,
D/wpa_supplicant( 2011): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2011):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011):   * freq=2412
D/wpa_supplicant( 2011):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/WifiStateMachine(  964): handleMessage: E msg.what=147461,
,D/wpa_supplicant( 2011):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011):   * Auth Type 0
D/wpa_supplicant( 2011):   * WPA Versions 0x2
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/wpa_supplicant( 2011): nl80211: Connect request send successfully,
D/wpa_supplicant( 2011): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
,D/wpa_supplicant( 2011): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2011): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2011): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ],
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2011): nl80211: Event message available
D/wpa_supplicant( 2011): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2011): nl80211: Connect event
D/wpa_supplicant( 2011): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2011): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2011): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2011): wlan0: Association info event
D/wpa_supplicant( 2011): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2011): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2011): wlan0: freq=2412 MHz
D/wpa_supplicant( 2011): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2011): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2011): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2011): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): scard is not null..
D/wpa_supplicant( 2011): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2011): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2011): TDLS: Remove peers on association
D/wpa_supplicant( 2011): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2011): EAPOL: enable timer tick
D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2011): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2011): wlan0: Cancelling scan request
,D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/wpa_supplicant( 2011): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 77 4f 17 cc 96 dd 0f f1 f1 2d f9 06 fb 43 15 ...
D/wpa_supplicant( 2011): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2011): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2011): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2011): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2011): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2011):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2011):   key_nonce - hexdump(len=32): 77 4f 17 cc 96 dd 0f f1 f1 2d f9 06 fb 43 15 95 b8 41 12 77 31 90 cd 82 ba de 07 39 13 f2 58 79
D/wpa_supplicant( 2011):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 77 4f 17 cc 96 dd 0f f1 f1 2d f9 06 fb 43 15 ...
D/wpa_supplicant( 2011): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2011): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2011): Get randomness: len=32 entropy=5
D/wpa_supplicant( 2011): WPA: Renewed SNonce - hexdump(len=32): 88 a5 59 fc 3d a7 f5 f4 b4 7d ae 29 f2 72 9e 97 b3 fb ba 3a 48 30 c9 e8 13 64 4f 91 69 0e 5c 16
D/wpa_supplicant( 2011): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2011): WPA: Nonce1 - hexdump(len=32): 88 a5 59 fc 3d a7 f5 f4 b4 7d ae 29 f2 72 9e 97 b3 fb ba 3a 48 30 c9 e8 13 64 4f 91 69 0e 5c 16
D/wpa_supplicant( 2011): WPA: Nonce2 - hexdump(len=32): 77 4f 17 cc 96 dd 0f f1 f1 2d f9 06 fb 43 15 95 b8 41 12 77 31 90 cd 82 ba de 07 39 13 f2 58 79
D/wpa_supplicant( 2011): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2011): WPA: PTK - hexdump(len=48): [REMOVED],
D/wpa_supplicant( 2011): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2011): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2011): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2011): WPA: KCK - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 2011): WPA: Derived Key MIC - hexdump(len=16): b7 fd 2d 2f de 25 4e 4d 5d f3 ec 09 15 54 ad 66
D/wpa_supplicant( 2011): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 88 a5 59 fc 3d a7 f5 f4 b4 7d ae 29 f2 72 9e ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 2011): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 77 4f 17 cc 96 dd 0f f1 f1 2d f9 06 fb 43 15 ...
D/wpa_supplicant( 2011): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2011): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2011): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2011): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2011):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2011):   key_nonce - hexdump(len=32): 77 4f 17 cc 96 dd 0f f1 f1 2d f9 06 fb 43 15 95 b8 41 12 77 31 90 cd 82 ba de 07 39 13 f2 58 79
D/wpa_supplicant( 2011):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_rsc - hexdump(len=8): cf fd 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2011):   key_mic - hexdump(len=16): ce 1d 26 0b 2e ce 77 eb 74 62 89 1b 63 50 9f c8
D/wpa_supplicant( 2011): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 77 4f 17 cc 96 dd 0f f1 f1 2d f9 06 fb 43 15 ...
D/wpa_supplicant( 2011): RSN: encrypted key data - hexdump(len=56): 12 0e cf 81 12 16 0f bc ce b3 09 5c ea c0 23 1b e2 08 f0 84 7d 53 18 80 db f4 8c 9e bd 9c b5 fb ...
D/wpa_supplicant( 2011): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2011): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2011): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2011): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 c5 dd ...
D/wpa_supplicant( 2011): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2011): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
,D/wpa_supplicant( 2011): wlan0: WPA: Sending EAPOL-Key 4/4
,D/wpa_supplicant( 2011): WPA: KCK - hexdump(len=16): [REMOVED],
,D/wpa_supplicant( 2011): WPA: Derived Key MIC - hexdump(len=16): 6d e1 63 21 d5 99 bf 3a 7a 4e c4 cb ea 23 b8 3a
,D/wpa_supplicant( 2011): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2011): wlan0: WPA: Installing PTK to the driver
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8351c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2011):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2011): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2011): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2011): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2011): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2011): WPA: RSC - hexdump(len=6): cf fd 00 00 00 00
,D/wpa_supplicant( 2011): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fb703a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2011):    broadcast key
I/wpa_supplicant( 2011): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2011): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2011): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2011): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=],
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2011): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2011): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2011): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2011): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2011): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2011): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2011): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2011): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2011): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2011): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2011): EAPOL authentication completed successfully
D/wpa_supplicant( 2011): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2011): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2011): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
,D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2011): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  964): ssid=NG700
D/WifiNative-wlan0(  964): id=0
D/WifiNative-wlan0(  964): mode=station
D/WifiNative-wlan0(  964): pairwise_cipher=CCMP
D/WifiNative-wlan0(  964): group_cipher=CCMP
D/WifiNative-wlan0(  964): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  964): wpa_state=COMPLETED
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  964): handleMessage: X
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-55ms what=147462 obj=android.net.wifi.StateChangeResult@431cb0f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-36ms what=147462 obj=android.net.wifi.StateChangeResult@43b000c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-36ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :false
I/AppUp4:CustModeStarterReceiver( 3782): onReceive
D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
D/AppUp4:CustFacade( 3782): isPhone : true
I/LicenseContentProvider( 3054): start selecting data
D/SIMObserver( 3054): simInfo1
I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6611 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 6611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6611): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2011): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2011): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2011): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
,D/CommandListener(  270): Setting iface cfg
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432e66f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432e66f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): addressUpdated: 192.168.1.154/24 on wlan0 flags 128 scope 0
D/CommandListener(  270): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  964): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-7ms what=131212 obj=192.168.1.154/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
I/LGEmail ( 6611): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2011): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2011): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2011): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
D/WifiP2pService(  964): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  964): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2011): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2011): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2011): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
,D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
,W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  964): handleMessage: X
,D/LGEmail ( 6611): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
,E/Parcel  (  574): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  964): handleMessage: X
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
E/Parcel  (  574): Reading a NULL string not supported here.
E/Parcel  (  574): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  574): Reading a NULL string not supported here.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,V/        (  270): RouteController
,W/BaseRuntimeLoader( 6611): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6611): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  270): RouteController
W/BaseRuntimeLoader( 6611): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6611): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  270): RouteController
,D/EAS     ( 6611): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6611): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/        (  270): RouteController
,V/        (  270): RouteController
,D/eas_req ( 6611): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/        (  270): RouteController
,I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4321): networkInfo.isConnected() = false
W/ProcessCpuTracker(  964): Skipping unknown process pid 6638
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  574): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  574): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  574): |CAC| updateNetCfgInfo
V/QCNEA   (  574): |CAC| *********************************************
V/QCNEA   (  574): |CAC|                   Netconfig               
V/QCNEA   (  574): |CAC| *********************************************
,V/QCNEA   (  574): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  574): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  574): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  574): |CAC| 	NetConfig: ip4        =192.168.1.154
V/QCNEA   (  574): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  574): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  574): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  574): |CAC| net type = 1
V/QCNEA   (  574): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  574): |CAC| Received ssid= NG700
V/QCNEA   (  574): |CAC| 	ssid           =NG700
V/QCNEA   (  574): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  574): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  574): |CAC| *********************************************
D/QCNEA   (  574): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  574): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  574): |CAC| dispatchNetCfg: updating:0xb73a28dc
D/QCNEA   (  574): |CAC| readCallback: read len:0, ret:-1, errno:11
,W/linker  ( 6611): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 6611): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6611): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 6611): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 6611): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/DhcpStateMachine(  964): DHCP request on wlan0
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/HtmlEditor( 6611): register_HtmlEditor, Success
D/HtmlEditor( 6611): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/HtmlEditor( 6611): register_HtmlEditorTimer, Success
D/HtmlEditor( 6611): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6611): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6611): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6611): register_HtmlEditorFont, Success
,D/HtmlEditor( 6611): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/HtmlEditor( 6611): register_HtmlEditorDrawText, Success
D/HtmlEditor( 6611): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6611): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6611): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6611): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 6611): JNI_OnLoad Success
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6649 uid=10052 gids={50052, 3003}
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
I/HubEmail( 6611): JNI_OnLoad()
I/HubEmail( 6611): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6611): registerNatives()
I/HubEmail( 6611): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6611): registerNativeMethods()
I/HubEmail( 6611): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 6611): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/HyLog   ( 6649): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6649): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6649): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): Killing 6001:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6649): [loadRssi] File not exist 
,V/LGRssiData( 6649): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6649): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 6649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/BaseRuntimeLoader( 6649): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6649): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 6649): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 6649): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6649): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 6649): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6649): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6649): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  964): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6672 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 6014:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
E/PhoneMonitor( 6649): onOtaspChanged old =0, new =3
V/PhoneMonitor( 6649): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/CheckinService( 1955): Checking schedule, now: 1453289705157 next: 1453289580862
,I/CheckinService( 1955): active receiver: enabled
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/CheckinService( 1955): Preparing to send checkin request
I/EventLogService( 1955): Accumulating logs since 1453289550538
D/HyLog   ( 6672): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6672): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6672): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinRequestBuilder( 1955): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1955): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6686 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 6686): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6686): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6686): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  964): Killing 4706:com.test.thalitest/u0a304 (adj 15): empty #17
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6699 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6699): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6699): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6699): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 6699): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6713 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  964): Killing 6032:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 6713): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6713): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6713): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+3ms, total 33ms
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/NFS     ( 6713): connectivityManager.getNetworkInfo = TYPE_WIFI
I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 27ms
,I/Wireless_Storage( 6713): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 6713): intf.getDisplayName() = lo
I/Wireless_Storage( 6713): intf.getDisplayName() = sit0
I/Wireless_Storage( 6713): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6713): intf.getDisplayName() = teql0
,I/Wireless_Storage( 6713): intf.getDisplayName() = wlan0
D/NFS     ( 6713): interface name:wlan0 name:wlan0
,D/NFS     ( 6713): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6713): interface name:wlan0 name:wlan0
D/NFS     ( 6713): addr:192.168.1.154 broadcast:192.168.1.255
,I/Wireless_Storage( 6713): CONNECT : WIFI_CONNECT
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 27ms
,I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6734 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 6210:com.google.android.talk/u0a77 (adj 15): empty #17
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6734): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6734): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6734): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x4331f4a0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1955): awaiting user notification for token
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6757 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,W/GAV2    ( 6734): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/HyLog   ( 6757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6757): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6757): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6757): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 6757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6757): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6757): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6757): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6757): install
,I/MultiDex( 6757): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6757): loading existing secondary dex files
,I/MultiDex( 6757): load found 3 secondary dex files
,I/MultiDex( 6757): install done
,D/dalvikvm( 6757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6757): VFY: unable to resolve instance field 61
,D/dalvikvm( 6757): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6757): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6757): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6757): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6757): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6757): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c2f8
D/dalvikvm( 6757): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c2f8
,D/dalvikvm( 6757): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c2f8, skipping init
,D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4281c2f8
D/dalvikvm( 6757): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4281c2f8
,V/JNIHelp ( 6757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/wpa_supplicant( 2011): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2011): EAPOL: disable timer tick
,D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4281c2f8
,D/dalvikvm( 6757): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4281c2f8
D/dalvikvm( 6757): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4281c2f8
,D/dalvikvm( 6757): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4281c2f8
,D/DhcpStateMachine(  964): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.154
,V/LgDhcpStateMachineHelper(  964): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  964): RunningState
,V/WebViewChromium( 6734): Binding Chromium to the main looper Looper (main, tid 1) {42814308}
,I/chromium( 6734): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6734): Initializing chromium process, renderers=0
,I/ProviderInstaller( 6757): Installed default security provider GmsCore_OpenSSL
,W/chromium( 6734): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6734): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6734): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6734): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6734): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6734): Remote Branch: 
I/Adreno-EGL( 6734): Local Patches: 
I/Adreno-EGL( 6734): Reconstruct Branch: 
,I/dalvikvm( 6757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6757): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6757): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6757): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6757): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6757): VFY: replacing opcode 0x6e at 0x0201
,I/NSApplication( 6734): Starting up...
,I/ActivityManager(  964): Killing 6258:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  276): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e09000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e09000
,I/ActivityManager(  964): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=6796 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/HyLog   ( 6796): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6796): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6796): I : /data/font/config/sfconfig.dat, No such file or directory (2)
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
D/WVCdm   (  276): PrepareKeyRequest: nonce=3785539717
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6796): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4281c7b8
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  964): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 6796): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4281c7b8
,D/jxcore_app_log( 6796): JniHelper::setJavaVM(0x416e1838), pthread_self() = 1074065748
,E/JX-Cordova( 6796): JXcore wasn't initialized yet
,D/QRemote ( 6565): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6565): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6565): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6565): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6565): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6565): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6520): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6520): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6565): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6565): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6565): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6565): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,I/ActivityManager(  964): Killing 6276:com.android.gallery3d/u0a27 (adj 15): empty #17
D/GCM     ( 1533): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1533): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1533): Proximity feature is not enabled.
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,V/GmsCoreStatsServiceLauncher( 1955): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/dalvikvm( 6757): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429b6690
,D/dalvikvm( 6757): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429b6690
,D/dalvikvm( 6757): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429b6690, skipping init
,D/WearableService( 1745): callingUid 10006, callindPid: 1745
,E/MDM     ( 1424): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1955): Restart initialization of location
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,W/Settings( 6757): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.154/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm(  964): GC_EXPLICIT freed 2357K, 50% free 30703K/60792K, paused 3ms+11ms, total 155ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 6757): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6818): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 6757): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6757): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 109ms
,I/Adreno-EGL( 6757): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6757): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6757): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6757): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6757): Remote Branch: 
I/Adreno-EGL( 6757): Local Patches: 
I/Adreno-EGL( 6757): Reconstruct Branch: 
,I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=1970773777
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1,
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 6757): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6757): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6757): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6757): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6757): Remote Branch: 
I/Adreno-EGL( 6757): Local Patches: 
I/Adreno-EGL( 6757): Reconstruct Branch: 
,I/Adreno-EGL( 6757): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6757): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6757): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6757): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6757): Remote Branch: 
I/Adreno-EGL( 6757): Local Patches: 
I/Adreno-EGL( 6757): Reconstruct Branch: 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1955): Classify the device as Phone.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3782): onReceive
,D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
,D/AppUp4:CustFacade( 3782): isPhone : true
,I/LicenseContentProvider( 3054): start selecting data
,D/SIMObserver( 3054): simInfo1
,I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3782): begin check event
,I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3782): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3782): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3782): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3782): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3782): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6611): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6329): DownloadService onCreate
,D/EAS     ( 6611): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 6611): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4321): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6649): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6699): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/NFS     ( 6713): connectivityManager.getNetworkInfo = TYPE_WIFI
I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/Wireless_Storage( 6713): CONNECT : WIFI_CONNECT
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 6329): in removeSpuriousFiles
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@42868ce8 on behalf of 6329
,W/Settings( 6611): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/DownloadManager( 6329): in trimDatabase
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 6329): DownloadService onStartCommand
D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,V/DownloadManager( 6329): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@4286a618 on behalf of 6329
V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@4286bea8 on behalf of 6329
,I/CheckinTask( 1955): Sending checkin request (11465 bytes)
,I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 6329): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3782): onReceive
D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
,D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
D/AppUp4:CustFacade( 3782): isPhone : true
,I/LicenseContentProvider( 3054): start selecting data
,D/SIMObserver( 3054): simInfo1
,I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
,I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6329): DownloadService onCreate
,I/DownloadManager( 6329): in removeSpuriousFiles
D/EAS     ( 6611): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6611): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@42870fe8 on behalf of 6329
,V/DownloadManager( 6329): DownloadService onStartCommand
V/DownloadManager( 6329): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 6329): in trimDatabase
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@42873c78 on behalf of 6329
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@42873778 on behalf of 6329
I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4321): networkInfo.isConnected() = true
D/PhoneState( 4321): setPdpRejectCasuse : false
,W/Settings( 6611): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6329): DownloadService onDestroy
,D/MobileConnectivityChangeReceiver( 6649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6649): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6699): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 6713): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6713): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 6699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 3941): GC_FOR_ALLOC freed 372K, 2% free 37942K/38604K, paused 21ms, total 21ms
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3782): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3782): onReceive
,D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
,D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
,D/AppUp4:CustFacade( 3782): isPhone : true
,I/LicenseContentProvider( 3054): start selecting data
,D/SIMObserver( 3054): simInfo1
,I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3782): begin check event
,I/AppUp4:CustModeStarterReceiver( 3782): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 6611): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6329): DownloadService onCreate
,D/EAS     ( 6611): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4321): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4321): networkInfo.isConnected() = true
,D/PhoneState( 4321): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6649): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2941): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6699): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6713): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6713): CONNECT : WIFI_CONNECT
,I/DownloadManager( 6329): in removeSpuriousFiles
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 6611): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2941): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@428782b8 on behalf of 6329
,I/DownloadManager( 6329): in trimDatabase
,V/DownloadManager( 6329): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@42879388 on behalf of 6329
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6329): DownloadService onStartCommand
E/LGDMClient( 2941): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 6329): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2941): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2941): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6329): created cursor android.database.sqlite.SQLiteCursor@4287be38 on behalf of 6329
,I/LGDMClient( 2941): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 6329): DownloadService onDestroy
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinRequestBuilder( 1955): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1955): Failed to find provider info for com.google.android.wearable.settings
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1533): Connected
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1533): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 1533): GC_EXPLICIT freed 1335K, 28% free 17982K/24832K, paused 3ms+6ms, total 55ms
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x433d25e8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1955): awaiting user notification for token
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1955): Classify the device as Phone.
,I/CheckinTask( 1955): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1955): Checking schedule, now: 1453289710376 next: 1453867106370
,I/CheckinService( 1955): active receiver: disabled
,I/CheckinService( 1955): Checking schedule, now: 1453289710414 next: 1453867106370
,I/CheckinService( 1955): active receiver: disabled
,D/GCM     ( 1533): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 6734): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ActivityManager(  964): Killing 6520:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): Killing 6292:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289711768001167; DSPS: 41326273; Offset: 1453288450590236275
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 4055): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4055): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  964): Handling package changes for user 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6938 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
D/HyLog   ( 6938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6938): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  964): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 6938): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6938): MmsConfig.loadMmsSettings
I/Babel   ( 6938): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6938): MmsConfig.loadFromDatabase
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/MediaCodecList( 6938): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6938): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 6938): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6938): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,V/GmsNetworkLocationProvi( 1424): DISABLE
,W/BaseRuntimeLoader( 6938): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6938): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Settings( 6938): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/BaseRuntimeLoader( 6938): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6938): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 6938): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6938): MmsConfig.loadFromResources
,E/Babel   ( 6938): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6938): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6938): [loadRssi] File not exist 
,V/LGRssiData( 6938): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6938): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6938): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6938): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6938): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3782): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3782): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3782): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3782): onReceive
D/AppUp4:CustFacade( 3782): Context : android.app.ReceiverRestrictedContext@428301b0
D/AppUp4:CustFacade( 3782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3782): isOpenOperator : true
,D/AppUp4:CustFacade( 3782): isPhone : true
,I/LicenseContentProvider( 3054): start selecting data
,D/SIMObserver( 3054): simInfo1
,I/AppUp4:EulaManager( 3782): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3782): begin check event
D/AppUp4:Utils( 3782): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3782): Event For Nothing, skip.
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6988 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6988): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6988): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6988): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6988): BUILD Country: EU
,I/SystemConfig( 6988): BUILD Operator: OPEN
,I/ActivityManager(  964): Killing 6565:com.lge.qremote/u0a96 (adj 15): empty #17
I/SystemConfig( 6988): systemFeature RCS result false
D/SystemConfig( 6988): refreshRcsSupport() :false
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7002 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  964): Killing 6329:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 7002): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7002): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7002): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2697): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  964): Killing 6611:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7019 uid=10050 gids={50050, 3003, 1028, 1015}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7019): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7019): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1955): GC_CONCURRENT freed 1999K, 22% free 19569K/24832K, paused 4ms+5ms, total 44ms
,I/dalvikvm( 7019): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7019): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7019): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 7019): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7019): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 7019): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7019): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7019): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 7019): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7019): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7019): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7019): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7019): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7019): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 7019): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7019): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7019): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7019): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7019): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7019): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 7019): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 7019): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7019): VFY: replacing opcode 0x6e at 0x001a
,I/ActivityManager(  964): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7053 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 7053): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 7053): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7053): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/dalvikvm( 7019): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 7019): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7019): VFY: replacing opcode 0x6e at 0x0049
,D/dalvikvm(  964): GC_EXPLICIT freed 2282K, 50% free 30799K/60792K, paused 4ms+15ms, total 154ms
,D/Finsky  ( 7019): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7019): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1955): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1955): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  964): Delaying start of: ServiceRecord{44fb8b48 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1955): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 7053): DownloadService onCreate
,I/DownloadManager( 7053): in removeSpuriousFiles
,V/DownloadManager( 7053): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7053): created cursor android.database.sqlite.SQLiteCursor@4285cb90 on behalf of 7053
,V/DownloadManager( 7053): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 7053): in trimDatabase
V/DownloadManager( 7053): created cursor android.database.sqlite.SQLiteCursor@42861ca8 on behalf of 7019
,V/DownloadManager( 7053): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 7053): DownloadService onStartCommand
,V/DownloadManager( 7053): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7053): created cursor android.database.sqlite.SQLiteCursor@42865198 on behalf of 7053
,V/DownloadManager( 7053): created cursor android.database.sqlite.SQLiteCursor@42866330 on behalf of 7053
,D/Finsky  ( 7019): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 7053): DownloadService onDestroy
,D/Finsky  ( 7019): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/IcingCorporaProvider( 2697): UpdateCorporaTask done [took 449 ms] updated apps [took 449 ms] 
I/ActivityManager(  964): Killing 6649:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7019): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7019): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7019): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7019): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7019): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7019): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 7019): Total arena pages for JIT: 11
,I/dalvikvm( 7019): Total arena pages for JIT: 12
I/dalvikvm( 7019): Total arena pages for JIT: 13
,I/dalvikvm( 7019): Total arena pages for JIT: 14
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1533): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7019): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7019): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7019): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7019): [1] DailyHygiene.reschedule: Scheduling new run in 280 minutes (failures=4)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-15ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  964): Checking http://216.58.209.78/generate_204
D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GAV4    ( 6938): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  964): Killing 6672:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d97bf8 stackId=0, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289731768475331; DSPS: 41981648; Offset: 1453288450590252675
,D/Finsky  ( 7019): [510] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7019): [1] 5.onFinished: Installation state replication succeeded.
,D/wpa_supplicant( 2011): wlan0: BSS: Remove id 7 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2011): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:12:7f:81]
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289751769814694; DSPS: 42637052; Offset: 1453288450590249265
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289760034, nextTick: 59990, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453289760037, nextTick: 59995, mDrawingTime: 0
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1453289771771232190; DSPS: 43292459; Offset: 1453288450590232435
,TIME-OUT KILL (timeout was 1200000ms)
```
