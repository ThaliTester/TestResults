#### Test 506502781c2754f_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1969): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1969): launchTask
W/dalvikvm( 1969): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1969): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1V2urj9Dg3411NbV83maoXeNiEZTLdI_e00MVi3jDF4ezKbL1Vzz3zxGTU0l5FURB31oMF1jkj61gpZ5TWEGmB6-W-Qg3CwnbgjFJcrQorHcKH8D6ZfKiqD8RfyB3q-zaFlQITQ0cT_cUI9vyE7ariHyDHeUuNmWmmGXVnaZjCpdPSwS0fMAe8LCyZxqueaY-IQPlnB
D/ChimeraCfgMgr( 1969): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1969): Module APK com.google.android.play.games already loaded
I/GoogleURLConnFactory( 1969): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1969): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1969): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1969): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1969): No vision deps
I/PeopleContactsSync( 1969): CP2 sync disabled
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1969): Using Auth Proxy for data requests.
W/BaseAppContext( 1969): Using Auth Proxy for data requests.
I/dalvikvm( 1969): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1969): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1969): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1969): Using Auth Proxy for data requests.
W/BaseAppContext( 1969): Using Auth Proxy for data requests.
W/BaseAppContext( 1969): Using Auth Proxy for data requests.
W/BaseAppContext( 1969): Using Auth Proxy for data requests.
W/GAV2    ( 4563): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  961): Killing 4012:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2}
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 1969): GC_CONCURRENT freed 1567K, 22% free 19454K/24832K, paused 4ms+5ms, total 53ms
D/dalvikvm( 1969): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/ConfigFetchService( 1969): fetch service done; releasing wakelock
I/ConfigFetchService( 1969): stopping self
D/ChimeraCfgMgr( 1969): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1969): Module APK com.google.android.play.games already loaded
I/Icing   ( 1969): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1969): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1969): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2029): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4623): 
D/AndroidRuntime( 4623): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4623): CheckJNI is OFF
D/dalvikvm( 4623): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4623): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4623): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4623): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4623): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4623): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4623): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4623): failed to load memtrack module: -2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4623): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4623
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
D/PermissionCache(  275): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (116 us)
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  961): startService SlideAside
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{43731b08 stackId=1, 2 tasks}
D/AndroidRuntime( 4623): Shutting down VM
D/UsbSettingsControl( 2617): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2617): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4623): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3999): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  961): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4641 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3999): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3999): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4641): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4641): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4641): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4641): Binding Chromium to the background looper Looper (main, tid 1) {42cea2c0}
I/chromium( 4641): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4641): Initializing chromium process, renderers=0
W/chromium( 4641): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4641): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4641): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4641): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4641): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4641): Remote Branch: 
I/Adreno-EGL( 4641): Local Patches: 
I/Adreno-EGL( 4641): Reconstruct Branch: 
I/dalvikvm( 4641): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4641): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4641): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4641): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4641): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4641): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4641): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4641): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4641): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4641): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4641): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4641): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4641): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4641): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4641): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4641): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4641): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4641): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4641): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4641): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4641): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4641): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4641): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4641): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4641): Enabling debug mode 0
,W/AwContents( 4641): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  961): IME STATUS OFF
,I/ActivityManager(  961): Displayed com.test.thalitest/.MainActivity: +471ms
,W/AwContents( 4641): nativeOnDraw failed; clearing to background color.
,I/ActivityManager( 4641): Timeline: Activity_idle id: android.os.BinderProxy@42ceb9a0 time:109988
,D/JsMessageQueue( 4641): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4641): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42cefa80
D/dalvikvm( 4641): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42cefa80
D/jxcore_app_log( 4641): JniHelper::setJavaVM(0x41c98808), pthread_self() = 1631167536
D/JX-Cordova( 4641): jxcore cordova android initializing
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3} time:110252
D/UsbSettings( 2617): [AUTORUN] onStop()
D/ActivityManager(  961): no-history finish of ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{42dc1318 ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 4641): GC_CONCURRENT freed 2803K, 13% free 21850K/24832K, paused 2ms+1ms, total 39ms
D/dalvikvm( 4641): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 4641): GC_FOR_ALLOC freed 205K, 13% free 21834K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4641): Grow heap (frag case) to 23.587MB for 96598-byte allocation
D/dalvikvm( 4641): GC_FOR_ALLOC freed 192K, 13% free 21856K/24928K, paused 23ms, total 23ms
I/dalvikvm-heap( 4641): Grow heap (frag case) to 23.656MB for 144892-byte allocation
D/dalvikvm( 4641): GC_FOR_ALLOC freed 254K, 13% free 21903K/25072K, paused 22ms, total 22ms
I/dalvikvm-heap( 4641): Grow heap (frag case) to 23.771MB for 217334-byte allocation
D/dalvikvm( 4641): GC_FOR_ALLOC freed 370K, 14% free 21978K/25288K, paused 22ms, total 22ms
I/dalvikvm-heap( 4641): Grow heap (frag case) to 23.948MB for 325996-byte allocation
D/dalvikvm( 4641): GC_FOR_ALLOC freed 570K, 14% free 22100K/25608K, paused 23ms, total 23ms
I/dalvikvm-heap( 4641): Grow heap (frag case) to 24.221MB for 488990-byte allocation
D/dalvikvm( 4641): GC_FOR_ALLOC freed 869K, 15% free 22277K/26088K, paused 23ms, total 23ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,D/dalvikvm( 4641): GC_FOR_ALLOC freed 1288K, 14% free 22534K/26088K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 25.228MB for 1100216-byte allocation
,D/dalvikvm( 4641): GC_CONCURRENT freed 1804K, 16% free 22923K/27164K, paused 2ms+2ms, total 41ms
,D/dalvikvm( 4641): GC_FOR_ALLOC freed 235K, 16% free 22875K/27164K, paused 24ms, total 24ms
I/dalvikvm-heap( 4641): Grow heap (frag case) to 26.086MB for 1650320-byte allocation
,D/dalvikvm( 4641): GC_CONCURRENT freed 1643K, 19% free 23434K/28776K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4641): GC_FOR_ALLOC freed 1431K, 19% free 23521K/28776K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 27.504MB for 2475476-byte allocation
,D/dalvikvm( 4641): GC_CONCURRENT freed 1962K, 23% free 24258K/31196K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 4641): GC_CONCURRENT freed 2410K, 22% free 24446K/31196K, paused 1ms+4ms, total 36ms
,D/dalvikvm( 4641): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 4641): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4641): GC_FOR_ALLOC freed 425K, 23% free 24326K/31196K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4641): Grow heap (frag case) to 29.470MB for 3713210-byte allocation
,D/dalvikvm( 4641): GC_CONCURRENT freed 362K, 20% free 27860K/34824K, paused 2ms+2ms, total 37ms
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,W/jxcore-log( 4641): Initializing JXcore engine
,W/jxcore-log( 4641): JXcore engine is ready
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,W/jxcore-log( 4641): Starting JXcore engine
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/jxcore-log( 4641): Platform android
W/jxcore-log( 4641): 
,W/jxcore-log( 4641): Process ARCH arm
W/jxcore-log( 4641): 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  961): Killing 4104:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
,I/jxcore-log( 4641): JXcore Cordova bridge is ready!
I/jxcore-log( 4641): 
,W/jxcore-log( 4641): JXcore engine is started
,I/chromium( 4641): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4641): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4641): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/GAV2    ( 4563): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ConfigService( 1535): onDestroy
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.481644 Y: -0.400940 Z: 9.747650 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.481644 .y:-0.400940 .z:9.747650
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.467453 Y: -0.407379 Z: 9.748779 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467453 .y:-0.407379 .z:9.748779
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/jxcore-log( 4641): Toggling radios to true
I/jxcore-log( 4641): 
,D/BluetoothManagerService(  961): Message: 20
,D/BluetoothManagerService(  961): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44366e78:true
,D/BluetoothAdapter( 4641): enable(): BT is already enabled..!
,D/WifiStateMachine(  961): handleMessage: E msg.what=131145
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doBoolean: DISCONNECT
,I/jxcore-log( 4641): Radios toggled
I/jxcore-log( 4641): 
,D/BluetoothManagerService(  961): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  961): New client listening to asynchronous messages
D/WifiService(  961): setWifiEnabled: true pid=4641, uid=10304
E/WifiService(  961): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  961): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  961): disconnect pid=4641, uid=10304
,D/WifiService(  961): reconnect pid=4641, uid=10304
I/jxcore-log( 4641): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4641): 
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2029): TDLS: Tear down peers
D/wpa_supplicant( 2029): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4641): Perf Test app loaded loaded
I/jxcore-log( 4641): 
,I/chromium( 4641): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Choreographer( 4641): Skipped 63 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2029): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2029): wlan0: Deauthentication notification
D/wpa_supplicant( 2029): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2029): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2029): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2029): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2029): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 2029): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7cf6d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2029):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2029): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 2029): nl80211: Ignore disconnect event triggered during reassociation
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: ConnectedState
W/Settings(  961): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  961): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131146
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiNative-wlan0(  961): doBoolean: RECONNECT
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2029): Fast associate: Old scan results
D/wpa_supplicant( 2029): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2029): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2029): wlan0: nl80211: scan request
D/wpa_supplicant( 2029): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147460
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection lost
D/WifiStateMachine(  961): Stopping DHCP and clearing IP
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  961): doBoolean: SET ps 1
I/jxcore-log( 4641): check test folder
I/jxcore-log( 4641): 
D/wpa_supplicant( 2029): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2029): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
,D/DhcpStateMachine(  961): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Clearing all IP addresses on wlan0
I/jxcore-log( 4641): found test : ./testFindPeers.js
I/jxcore-log( 4641): 
D/WifiStateMachine(  961): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  961): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  961): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  961): transitionTo: destState=DisconnectedState
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
D/QCNEA   (  522): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  522): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  522): |CAC| updateNetCfgInfo
V/QCNEA   (  522): |CAC| *********************************************
V/QCNEA   (  522): |CAC|                   Netconfig               
V/QCNEA   (  522): |CAC| *********************************************
V/QCNEA   (  522): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  522): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  522): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  522): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  522): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  522): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  522): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  522): |CAC| *********************************************
D/QCNEA   (  522): |CAC| Received bssid= 
D/QCNEA   (  522): |CAC| net type = 3
V/QCNEA   (  522): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  522): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  522): |CAC| 	ssid           =NG700
V/QCNEA   (  522): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  522): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  522): |CAC| *********************************************
D/QCNEA   (  522): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  522): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  522): |CAC| dispatchNetCfg: updating:0xb78f78dc
,D/QCNEA   (  522): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  522): Reading a NULL string not supported here.
,E/Parcel  (  522): Reading a NULL string not supported here.
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  961): invokeExitMethods: DisconnectingState
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  961): hidePasspointNotification off =false
D/QcConnectivityService(  961): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  961): Attempting to switch to mobile
D/QcConnectivityService(  961): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  961): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  271): RouteController
,I/jxcore-log( 4641): found test : ./testSendData.js
I/jxcore-log( 4641): 
,V/        (  271): RouteController
,I/ActivityManager(  961): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4689 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  271): RouteController
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
,D/HyLog   ( 4689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4689): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,V/        (  271): RouteController
,W/NetworkManagementService(  961): route cmd failed: 
W/NetworkManagementService(  961): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  961): '
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  961): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  961): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  961): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  961): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  961): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  961): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/jxcore-log( 4641): found test : ./testSendData2.js
I/jxcore-log( 4641): 
,D/NetUtils(  961): android_net_utils_resetConnections in env=0x5c834690 clazz=0x6cd00001 iface=wlan0 mask=0x3
,E/jxcore  ( 4641): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 4641): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
D/QcConnectivityService(  961): resetConnections(wlan0, 3)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/PCSuite ( 4689): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/NativeCrypto( 1535): Read error: ssl=0x614f1910: I/O error during system call, Connection timed out
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/PCSuite ( 4689): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4689): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,V/NativeCrypto( 1535): SSL shutdown failed: ssl=0x614f1910: I/O error during system call, Broken pipe
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  961): battery changed pluggedType: 2
,I/ActivityManager(  961): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4726 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  961): Killing 3142:android.process.media/u0a23 (adj 15): empty #17
,D/dalvikvm(  276): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
,D/HyLog   ( 4726): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4726): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4726): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
,D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 17ms
,D/QRemote ( 4726): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/QRemote ( 4726): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4726): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4726): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4726): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4726): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4726): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4726): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4726): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  961): Killing 3900:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  961): StoppedState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false,
D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3747): onReceive
,D/AppUp4:CustFacade( 3747): Context : android.app.ReceiverRestrictedContext@42cfc188
D/AppUp4:CustFacade( 3747): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3747): isOpenOperator : true
,D/AppUp4:CustFacade( 3747): isPhone : true
,I/LicenseContentProvider( 3004): start selecting data
,D/SIMObserver( 3004): simInfo1
,I/AppUp4:EulaManager( 3747): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3747): begin check event
,I/AppUp4:CustModeStarterReceiver( 3747): Event For GoodConnectivity
,I/ActivityManager(  961): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4757 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 4757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4757): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4757): DownloadService onCreate
,I/DownloadManager( 4757): in removeSpuriousFiles
,D/EAS     ( 4544): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2029): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2029): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2029): nl80211: Received scan results (11 BSSes)
D/wpa_supplicant( 2029): nl80211: Survey data missing
D/wpa_supplicant( 2029): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2029): wlan0: BSS: Add new id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 6 BSSID 8c:04:ff:b9:af:25 SSID 'SALVADOR'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 9 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 10 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Add new id 11 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): BSS: last_scan_res_used=11/32 last_scan_full=0
D/wpa_supplicant( 2029): wlan0: New scan results available
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2029): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2029): WPS: AP 64:7c:34:12:7f:81 type 0 added
,D/wpa_supplicant( 2029): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2029): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2029): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[1] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[3] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): WPS: AP[4] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2029): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2029): wlan0: 0: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62
D/wpa_supplicant( 2029): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2029): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-65 wps
D/wpa_supplicant( 2029): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2029): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 1
,D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2029): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7cf85a8  current_ssid=0x0
D/wpa_supplicant( 2029): scard is not null..
D/wpa_supplicant( 2029): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2029): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
,D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2029): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2029): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2029): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2029): RSN: PMKSA cache search - network_ctx=0xb7cf85a8 try_opportunistic=0
D/wpa_supplicant( 2029): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2029): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2029): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2029): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2029): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2029): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2029): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2029): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2029): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2029): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2029): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2029): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2029): nl80211: Unsubscribe mgmt frames handle 0xb7cf7590 (mode change)
D/wpa_supplicant( 2029): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0c
,D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2029): nl80211: Register frame type=0xd0 nl_handle=0xb7cf7590
D/wpa_supplicant( 2029): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 2029): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2029):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029):   * freq=2412
D/wpa_supplicant( 2029):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2029):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029):   * Auth Type 0
D/wpa_supplicant( 2029):   * WPA Versions 0x2
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 a0:c5:62:7a:49:97]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 8c:04:ff:b9:af:25]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:96]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ab]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 fc:94:e3:11:35:3a]
D/wpa_supplicant( 2029): nl80211: Connect request send successfully
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2029): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 fe:94:e3:11:35:3c]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 44:e9:dd:10:c0:ad]
D/WifiStateMachine(  961): handleMessage: E msg.what=147461
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  961): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2029): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,V/DownloadManager( 4757): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4757): DownloadService onStartCommand
D/EAS     ( 4544): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
,D/WifiStateMachine(  961): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
,V/DownloadManager( 4757): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d27400 on behalf of 4757
,V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d252c0 on behalf of 4757
,D/eas_req ( 4544): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4757): in trimDatabase
,V/DownloadManager( 4757): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4757): DownloadService onDestroy
,V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d2b698 on behalf of 4757
,I/LgeMiscReceiver( 4278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4278): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4278): networkInfo.isConnected() = false
,W/linker  ( 4544): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4544): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4544): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4544): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4544): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4544): register_HtmlEditor, Success
D/HtmlEditor( 4544): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4544): register_HtmlEditorTimer, Success
D/HtmlEditor( 4544): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4544): register_HtmlEditorDownloader, Success
,D/HtmlEditor( 4544): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4544): register_HtmlEditorFont, Success
D/HtmlEditor( 4544): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4544): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4544): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4544): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4544): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4544): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4544): JNI_OnLoad Success
,I/HubEmail( 4544): JNI_OnLoad()
I/HubEmail( 4544): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4544): registerNatives()
I/HubEmail( 4544): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4544): registerNativeMethods()
,I/HubEmail( 4544): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4544): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 2029): nl80211: Event message available
D/wpa_supplicant( 2029): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2029): nl80211: Connect event
D/wpa_supplicant( 2029): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2029): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2029): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2029): wlan0: Association info event
D/wpa_supplicant( 2029): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2029): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2029): wlan0: freq=2412 MHz
D/wpa_supplicant( 2029): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2029): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2029): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2029): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): scard is not null..
D/wpa_supplicant( 2029): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2029): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2029): TDLS: Remove peers on association
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2029): EAPOL: enable timer tick
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): wlan0: Cancelling scan request
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): n,l80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  961): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  961): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
I/ActivityManager(  961): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4788 uid=10052 gids={50052, 3003}
I/ActivityManager(  961): Killing 4264:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
D/wpa_supplicant( 2029): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 53 b1 2b b6 c8 09 60 68 9d 4f 3f 35 9e be 2e ...
D/wpa_supplicant( 2029): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2029): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2029): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2029): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2029): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2029):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2029):   key_nonce - hexdump(len=32): 53 b1 2b b6 c8 09 60 68 9d 4f 3f 35 9e be 2e 80 5a fd 72 07 fe 10 7a 49 ca 6e f7 64 e7 6f 13 02
D/wpa_supplicant( 2029):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 53 b1 2b b6 c8 09 60 68 9d 4f 3f 35 9e be 2e ...
D/wpa_supplicant( 2029): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2029): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2029): Get randomness: len=32 entropy=11
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/wpa_supplicant( 2029): WPA: Renewed SNonce - hexdump(len=32): 37 99 d8 c5 c1 6d ce 48 da 5c a2 fd b0 40 96 c0 99 67 e5 35 99 43 fa 17 6a 29 85 12 87 aa 45 45
D/wpa_supplicant( 2029): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): WPA: Nonce1 - hexdump(len=32): 37 99 d8 c5 c1 6d ce 48 da 5c a2 fd b0 40 96 c0 99 67 e5 35 99 43 fa 17 6a 29 85 12 87 aa 45 45
D/wpa_supplicant( 2029): WPA: Nonce2 - hexdump(len=32): 53 b1 2b b6 c8 09 60 68 9d 4f 3f 35 9e be 2e 80 5a fd 72 07 fe 10 7a 49 ca 6e f7 64 e7 6f 13 02
D/wpa_supplicant( 2029): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2029): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2029): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2029): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2029): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): WPA: Derived Key MIC - hexdump(len=16): a9 2d 08 06 37 c4 1e 4e d5 58 f5 f7 b6 fe 01 92
D/wpa_supplicant( 2029): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 37 99 d8 c5 c1 6d ce 48 da 5c a2 fd b0 40 96 ...
D/HyLog   ( 4788): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4788): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4788): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
D/wpa_supplicant( 2029): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 53 b1 2b b6 c8 09 60 68 9d 4f 3f 35 9e be 2e ...
D/wpa_supplicant( 2029): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2029): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2029): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2029): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2029):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2029):   key_nonce - hexdump(len=32): 53 b1 2b b6 c8 09 60 68 9d 4f 3f 35 9e be 2e 80 5a fd 72 07 fe 10 7a 49 ca 6e f7 64 e7 6f 13 02
D/wpa_supplicant( 2029):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_rsc - hexdump(len=8): f7 72 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2029):   key_mic - hexdump(len=16): 89 d7 6d e1 f5 5e 35 87 74 7b 32 96 06 5a c5 74
D/wpa_supplicant( 2029): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 53 b1 2b b6 c8 09 60 68 9d 4f 3f 35 9e be 2e ...
D/wpa_supplicant( 2029): RSN: encrypted key data - hexdump(len=56): 8f 84 b4 f1 a6 b2 3f 3d 48 b6 31 25 01 be 9d 51 5c 6a 25 3d ac a6 a4 66 8d 02 7b c8 d8 dc fc 04 ...
D/wpa_supplicant( 2029): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2029): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2029): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2029): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 4b 0f ...
D/wpa_supplicant( 2029): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2029): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2029): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2029): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): WPA: Derived Key MIC - hexdump(len=16): 20 e8 91 37 94 1a 31 b2 40 96 d9 8d b6 39 b7 62
D/wpa_supplicant( 2029): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2029): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb7cf7c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2029):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2029): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2029): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2029): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2029): WPA: RSC - hexdump(len=6): f7 72 00 00 00 00
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ec903a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2029):    broadcast key
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
I/wpa_supplicant( 2029): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2029): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2029): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2029): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2029): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2029): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2029): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2029): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2029): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2029): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2029): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2029): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2029): EAPOL authentication completed successfully
D/wpa_supplicant( 2029): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2029): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2029): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  961): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection established
D/WifiNative-wlan0(  961): doString: STATUS
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2029): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  961):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  961): ssid=NG700
D/WifiNative-wlan0(  961): id=0
D/WifiNative-wlan0(  961): mode=station
D/WifiNative-wlan0(  961): pairwise_cipher=CCMP
D/WifiNative-wlan0(  961): group_cipher=CCMP
D/WifiNative-wlan0(  961): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  961): wpa_state=COMPLETED
D/WifiNative-wlan0(  961): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  961): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  961): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  961): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  961): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  961): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  961): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  961): handleMessage: X
D/DhcpStateMachine(  961): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/DhcpStateMachine(  961): WaitBeforeStartState
D/WifiStateMachine(  961): ObtainingIpState{ when=-11ms what=147462 obj=android.net.wifi.StateChangeResult@441c54a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-8ms what=147462 obj=android.net.wifi.StateChangeResult@441c79f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-8ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
D/wpa_supplicant( 2029): nl80211: survey data missing!
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=196612
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 1
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4788): [loadRssi] File not exist 
V/LGRssiData( 4788): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4788): [loadFeatureFromXml] *** start feature loading from xml
D/MobileConnectivityChangeReceiver( 4788): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4788): onReceive CONNECTIVITY_CHANGE networkType=1
W/BaseRuntimeLoader( 4788): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4788): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4788): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4788): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4788): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4788): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4788): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4788): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4788): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  961): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4802 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  961): Killing 4469:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4802): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4802): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4802): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  961): doBoolean: SET ps 0
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  961):    returned null
E/WifiStateMachine(  961): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  961):    returned null
D/DhcpStateMachine(  961): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  961): DHCP Start wake lock is acquired.
E/WifiStateMachine(  961): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  271): Setting iface cfg
,D/WifiStateMachine(  961): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  271): Trying to bring up wlan0
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4352af40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4352af40 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  961): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4815 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  961): Killing 4502:com.google.android.partnersetup/u0a9 (adj 15): empty #17
V/LgDhcpStateMachineHelper(  961): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=196613
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  961): doBoolean: SET ps 1
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2029): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2029): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2029): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
,D/WifiStateMachine(  961): DHCP successful
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  961): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: ObtainingIpState
,D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  961): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState enter
,D/WifiStateMachine(  961): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
E/Parcel  (  522): Reading a NULL string not supported here.
D/WifiStateMachine(  961): handleMessage: E msg.what=135190
D/ConnectivityServiceHSM(  961): send additional Connectivity Action
D/WifiStateMachine(  961): processMsg: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  961): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  961): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): CaptivePortalCheckState enter
D/WifiStateMachine(  961): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  961): handleMessage: X
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  522): Reading a NULL string not supported here.
,E/Parcel  (  522): Reading a NULL string not supported here.
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
W/WifiStateTracker(  961): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  961): 
W/WifiStateTracker(  961):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  961):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  961): handleMessage: E msg.what=131092
D/WifiStateMachine(  961): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  961): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4815): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  961): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/WifiStateMachine(  961): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/WifiStateMachine(  961): transitionTo: destState=ConnectedState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  961): handleMessage: X
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ActivityThread(  961): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  961): handleConnectivityChange: preConnState=2 connState=1
,V/        (  271): RouteController
,I/ActivityManager(  961): Killing 4531:com.lge.bnr/1000 (adj 15): empty #17
D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/        (  271): RouteController
D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/        (  271): RouteController
V/        (  271): RouteController
I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/        (  271): RouteController
I/ActivityManager(  961): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4835 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/QCNEA   (  522): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  522): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  522): |CAC| updateNetCfgInfo
V/QCNEA   (  522): |CAC| *********************************************
V/QCNEA   (  522): |CAC|                   Netconfig               
V/QCNEA   (  522): |CAC| *********************************************
V/QCNEA   (  522): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  522): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  522): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  522): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  522): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  522): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  522): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  522): |CAC| *********************************************
D/QCNEA   (  522): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  522): |CAC| net type = 1
V/QCNEA   (  522): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  522): |CAC| Received ssid= NG700
V/QCNEA   (  522): |CAC| 	ssid           =NG700
V/QCNEA   (  522): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  522): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  522): |CAC| *********************************************
D/QCNEA   (  522): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  522): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  522): |CAC| dispatchNetCfg: updating:0xb78f78dc
,D/QCNEA   (  522): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  961): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  961): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  961): GC_EXPLICIT freed 23710K, 49% free 29732K/57552K, paused 2ms+8ms, total 128ms
,D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1969): Checking schedule, now: 1450658023576 next: 1450657967095
,I/CheckinService( 1969): active receiver: enabled
,I/CheckinService( 1969): Preparing to send checkin request
,I/EventLogService( 1969): Accumulating logs since 1450657934404
,D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  961): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4874 uid=10101 gids={50101, 1028, 1015, 3003}
,I/CheckinRequestBuilder( 1969): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4874): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 4874): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4874): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4874): intf.getDisplayName() = lo
,I/Wireless_Storage( 4874): intf.getDisplayName() = sit0
I/Wireless_Storage( 4874): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4874): intf.getDisplayName() = teql0
I/Wireless_Storage( 4874): intf.getDisplayName() = wlan0
,D/NFS     ( 4874): interface name:wlan0 name:wlan0
D/NFS     ( 4874): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4874): interface name:wlan0 name:wlan0
D/NFS     ( 4874): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4874): CONNECT : WIFI_CONNECT
,D/dalvikvm( 1535): GC_EXPLICIT freed 1039K, 29% free 17811K/24832K, paused 1ms+3ms, total 25ms
,I/ActivityManager(  961): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4899 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  961): Killing 4152:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4899): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4899): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4899): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 4899): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1969): awaiting user notification for token
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x42e73bc8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  961): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4926 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4926): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4926): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4926): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4926): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4926): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4926): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4926): VFY: replacing opcode 0x62 at 0x005e
V/WebViewChromium( 4899): Binding Chromium to the main looper Looper (main, tid 1) {42ce82f0}
I/MultiDex( 4926): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4926): install
I/chromium( 4899): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/MultiDex( 4926): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/BrowserProcessMain( 4899): Initializing chromium process, renderers=0
,I/MultiDex( 4926): loading existing secondary dex files
,I/MultiDex( 4926): load found 3 secondary dex files
,I/MultiDex( 4926): install done
,W/chromium( 4899): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4899): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4899): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4899): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4899): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4899): Remote Branch: 
I/Adreno-EGL( 4899): Local Patches: 
I/Adreno-EGL( 4899): Reconstruct Branch: 
,D/dalvikvm( 4926): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4926): VFY: unable to resolve instance field 61
,D/dalvikvm( 4926): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 4926): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4926): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4926): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4926): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4926): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4926): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4926): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4926): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4926): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42cef580
,D/dalvikvm( 4926): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42cef580
,D/dalvikvm( 4926): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42cef580, skipping init
,D/dalvikvm( 4926): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42cef580
D/dalvikvm( 4926): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42cef580
,V/JNIHelp ( 4926): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/NSApplication( 4899): Starting up...
,I/ActivityManager(  961): Killing 4167:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4726): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4726): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 4926): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42cef580
,D/dalvikvm( 4926): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42cef580
D/dalvikvm( 4926): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42cef580
,D/dalvikvm( 4926): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42cef580
,D/QRemote ( 4726): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4726): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4726): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4726): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4689): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4689): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4726): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4726): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4726): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4726): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/DhcpStateMachine(  961): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  961): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  961): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
,V/LgDhcpStateMachineHelper(  961): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  961): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  961): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  961): RunningState
,I/ProviderInstaller( 4926): Installed default security provider GmsCore_OpenSSL
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
D/GCM     ( 1535): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1535): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1535): Proximity feature is not enabled.
V/GmsCoreStatsServiceLauncher( 1969): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WearableService( 1878): callingUid 10006, callindPid: 1878
I/dalvikvm( 4926): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4926): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4926): VFY: replacing opcode 0x6e at 0x000d
,E/MDM     ( 1425): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/dalvikvm( 4926): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4926): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4926): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1969): Restart initialization of location
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  278): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2019000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2019000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3513780665
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2029): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2029): EAPOL: disable timer tick
,D/dalvikvm( 4926): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ead7b8
,D/dalvikvm( 4926): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ead7b8
,D/dalvikvm( 4926): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42ead7b8, skipping init
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  961): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4926): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4960): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4926): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4926): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 67ms
,I/Adreno-EGL( 4926): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4926): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4926): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4926): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4926): Remote Branch: 
I/Adreno-EGL( 4926): Local Patches: 
I/Adreno-EGL( 4926): Reconstruct Branch: 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  961): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  961): processMsg: SupplicantStartedState
,D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  961): handleMessage: X
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  961): send additional Connectivity Action
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QcConnectivityService(  961): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  961):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  961): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,I/Adreno-EGL( 4926): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4926): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4926): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4926): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4926): Remote Branch: 
I/Adreno-EGL( 4926): Local Patches: 
I/Adreno-EGL( 4926): Reconstruct Branch: 
,I/Adreno-EGL( 4926): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4926): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4926): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4926): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4926): Remote Branch: 
I/Adreno-EGL( 4926): Local Patches: 
I/Adreno-EGL( 4926): Reconstruct Branch: 
,I/dalvikvm( 4641): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4641): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4641): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4641): Shutting down VM
,W/dalvikvm( 4641): threadid=1: thread exiting with uncaught exception (group=0x41ca9e48)
E/AndroidRuntime( 4641): FATAL EXCEPTION: main
E/AndroidRuntime( 4641): Process: com.test.thalitest, PID: 4641
E/AndroidRuntime( 4641): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4641): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4641): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4641): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4641): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4641): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4641): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4641): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4641): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4641): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4641): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4641): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4641): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4641): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4641): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4641): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4641): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  961):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4926): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
I/WVCdm   (  278): CdmEngine::OpenSession
D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  278): PrepareKeyRequest: nonce=1261175639
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1969): Sending checkin request (11587 bytes)
,W/ActivityManager(  961): Activity pause timeout for ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43731b08 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  961): moveHomeStack:
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1448): getIsInUseVoLTE : false
I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
D/WeatherAncestor( 1843): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:33:45
D/UpdateThreadPoolManager( 1843): 2 : This is isUpdating : false
D/WeatherQuickCover( 1843): 2 : quick cover state : opened : 0
D/WeatherService( 1843): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1843): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1843): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1843): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1843): 2 : TimeTick Receiver Register
D/WeatherAncestor( 1843): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:33:45
D/WeatherService( 1843): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1843): 2 : quick cover state : opened : 0
D/Weather.Utils( 1843): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1843): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1843): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1843): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1843): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1843): 2 : This is isUpdating : false
D/WeatherService( 1843): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1843): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1843): 2 : Map key string is -2
D/lim     ( 1843): 2 : time = 01:33
I/WeatherReflect( 1843): Model Name : LG-D802
D/WeatherTheme( 1843): 2 : Different view - status_min_formatted : 32 != 33
D/WeatherTheme( 1843): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1843): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1843): 2 : Fixed theme : optimus
D/WeatherTheme( 1843): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1843): 2 : quick cover state : opened : 0
D/Weather.Utils( 1843): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1843): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1843): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/dalvikvm( 1488): GC_CONCURRENT freed 4951K, 8% free 60619K/65752K, paused 1ms+3ms, total 27ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 6708K, 10% free 70955K/78508K, paused 32ms, total 32ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
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
,D/dalvikvm( 1488): GC_FOR_ALLOC freed 5264K, 9% free 62217K/68244K, paused 25ms, total 25ms
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@42ce6f10 time:119832
,D/UsbSettings( 2617): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2617): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2617): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2617): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{43062840 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,I/CheckinRequestBuilder( 1969): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1} time:119870
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1969): awaiting user notification for token
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,I/CheckinTask( 1969): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1969): Checking schedule, now: 1450658025958 next: 1451235421955
,I/CheckinService( 1969): active receiver: disabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  961): GC_CONCURRENT freed 2222K, 47% free 30823K/57552K, paused 3ms+7ms, total 106ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 101ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 65ms
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x44945610: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1535): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1535): Connected
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1535): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3747): onReceive
,D/AppUp4:CustFacade( 3747): Context : android.app.ReceiverRestrictedContext@42cfc188
D/AppUp4:CustFacade( 3747): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3747): isOpenOperator : true
,D/AppUp4:CustFacade( 3747): isPhone : true
,I/LicenseContentProvider( 3004): start selecting data
,D/SIMObserver( 3004): simInfo1
,I/AppUp4:EulaManager( 3747): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3747): begin check event
,I/AppUp4:CustModeStarterReceiver( 3747): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3747): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3747): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3747): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3747): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3747): handleAsyncCustNotification do not startCustService
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/EAS     ( 4544): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4544): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4544): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4757): DownloadService onCreate
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 4757): in removeSpuriousFiles
V/DownloadManager( 4757): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4278): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 4788): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4788): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d2efe8 on behalf of 4757
W/Settings( 4544): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4757): DownloadService onStartCommand
V/DownloadManager( 4757): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d31ac0 on behalf of 4757
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/DownloadManager( 4757): in trimDatabase
V/DownloadManager( 4757): DownloadService onDestroy
I/NFS     ( 4874): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4874): CONNECT : WIFI_CONNECT
V/DownloadManager( 4757): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d33600 on behalf of 4757
E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3747): onReceive
,D/AppUp4:CustFacade( 3747): Context : android.app.ReceiverRestrictedContext@42cfc188
D/AppUp4:CustFacade( 3747): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3747): isOpenOperator : true
D/AppUp4:CustFacade( 3747): isPhone : true
,I/LicenseContentProvider( 3004): start selecting data
,D/SIMObserver( 3004): simInfo1
,I/AppUp4:EulaManager( 3747): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3747): begin check event
,I/AppUp4:CustModeStarterReceiver( 3747): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4757): DownloadService onCreate
,I/DownloadManager( 4757): in removeSpuriousFiles
V/DownloadManager( 4757): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d36d18 on behalf of 4757
D/EAS     ( 4544): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4544): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4757): in trimDatabase
,V/DownloadManager( 4757): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d38b88 on behalf of 4757
,V/DownloadManager( 4757): DownloadService onStartCommand
,V/DownloadManager( 4757): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d3a880 on behalf of 4757
,V/DownloadManager( 4757): DownloadService onDestroy
,I/LgeMiscReceiver( 4278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4278): networkInfo.isConnected() = true
,D/PhoneState( 4278): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4788): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4788): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4544): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4874): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4874): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3747): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3747): onReceive
,D/AppUp4:CustFacade( 3747): Context : android.app.ReceiverRestrictedContext@42cfc188
D/AppUp4:CustFacade( 3747): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3747): isOpenOperator : true
,D/AppUp4:CustFacade( 3747): isPhone : true
,I/LicenseContentProvider( 3004): start selecting data
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/SIMObserver( 3004): simInfo1
,I/AppUp4:EulaManager( 3747): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3747): begin check event
,I/AppUp4:CustModeStarterReceiver( 3747): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4544): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4757): DownloadService onCreate
,D/EAS     ( 4544): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4278): networkInfo.isConnected() = true
,D/PhoneState( 4278): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4788): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4788): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2863): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4835): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4874): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4874): CONNECT : WIFI_CONNECT
,I/DownloadManager( 4757): in removeSpuriousFiles
,V/DownloadManager( 4757): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d3ea48 on behalf of 4757
I/DownloadManager( 4757): in trimDatabase
V/DownloadManager( 4757): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 2863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
W/Settings( 4544): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d40440 on behalf of 4757
,I/LGDMClient( 2863): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 4757): DownloadService onStartCommand
,V/DownloadManager( 4757): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4757): created cursor android.database.sqlite.SQLiteCursor@42d425f0 on behalf of 4757
,E/LGDMClient( 2863): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2863): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,V/DownloadManager( 4757): DownloadService onDestroy
,D/LGDMClient( 2863): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2863): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/WifiServiceExtension(  961): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4899): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  961): Killing 4689:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  961): Killing 4563:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,D/Finsky  ( 4185): [393] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4185): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  961): Killing 4726:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.471237 Y: -0.398621 Z: 9.764145 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471237 .y:-0.398621 .z:9.764145
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0,
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0,
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.462830 Y: -0.407776 Z: 9.764069 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462830 .y:-0.407776 .z:9.764069,
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0,
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  961): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  961): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5110 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/administrator(  961): Handling package changes for user 0
,E/SlideAside( 3999): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/SlideAside( 3999): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5110): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5110): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5110): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5110): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5110): MmsConfig.loadMmsSettings
,I/Babel   ( 5110): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5110): MmsConfig.loadFromDatabase
I/MediaCodecList( 5110): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5110): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 5110): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5110): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5110): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 5110): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5110): MmsConfig.loadFromResources
,E/Babel   ( 5110): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5110): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5110): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/LGRssiData( 5110): [loadRssi] File not exist 
V/LGRssiData( 5110): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5110): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:Utils( 3747): [getPackageName] uri : package:com.google.android.gms
V/TelephonyAutoProfiling( 5110): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5110): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5110): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4  ( 3747): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3747): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3747): onReceive
,V/GmsNetworkLocationProvi( 1425): DISABLE
D/AppUp4:CustFacade( 3747): Context : android.app.ReceiverRestrictedContext@42cfc188
D/AppUp4:CustFacade( 3747): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3747): isOpenOperator : true
,D/AppUp4:CustFacade( 3747): isPhone : true
,I/LicenseContentProvider( 3004): start selecting data
,D/SIMObserver( 3004): simInfo1
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppUp4:EulaManager( 3747): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3747): begin check event
D/AppUp4:Utils( 3747): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3747): Event For Nothing, skip.
,I/ActivityManager(  961): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5160 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5160): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5160): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5160): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  961): applying state to connected service
,D/LocationProviderProxy(  961): applying state to connected service
I/ActivityManager(  961): Killing 4641:com.test.thalitest/u0a304 (adj 15): empty #17
,I/SystemConfig( 5160): BUILD Country: EU
,I/SystemConfig( 5160): BUILD Operator: OPEN
I/ActivityManager(  961): Killing 4757:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  961): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5174 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,I/SystemConfig( 5160): systemFeature RCS result false
,D/SystemConfig( 5160): refreshRcsSupport() :false
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,D/dalvikvm(  276): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+2ms, total 18ms
I/WindowState(  961): WIN DEATH: Window{45314f70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  961): Client connection lost with reason: 4
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,D/HyLog   ( 5174): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5174): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5174): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{44283780 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,W/Binder  ( 1309): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1309): java.lang.NullPointerException
W/Binder  ( 1309): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1309): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1309): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1309): 	at dalvik.system.NativeStart.run(Native Method)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/InputMethodManagerService(  961): IME STATUS OFF
W/InputMethodManagerService(  961): Got RemoteException sending setActive(false) notification to pid 4641 uid 10304
D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
D/HeadsetStateMachine( 1213): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 16ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1213): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
,I/IcingCorporaProvider( 2689): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  961): Killing 4544:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{430be8d8 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1969): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1969): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  961): Delaying start of: ServiceRecord{4469cf50 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1969): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1969): GC_CONCURRENT freed 1922K, 22% free 19552K/24832K, paused 2ms+4ms, total 34ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2689): UpdateCorporaTask done [took 209 ms] updated apps [took 209 ms] 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  961): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  961): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  961): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  961): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  961): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5110): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658040030, nextTick: 59994, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658040068, nextTick: 59965, mDrawingTime: 0
,D/WeatherService( 1843): 2 : TimeTick Intent has been received, Time(hour:min:sec) 1:34:0
,D/WeatherService( 1843): 2 : TimeTick Intent And Screen On
,D/WeatherService( 1843): 2 : SDK version : 19
,D/WeatherQuickCover( 1843): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1843): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1843): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1843): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1843): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1843): 2 : This is isUpdating : false
D/WeatherService( 1843): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1843): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1843): 2 : Map key string is -2
,D/lim     ( 1843): 2 : time = 01:34
,I/WeatherReflect( 1843): Model Name : LG-D802
D/WeatherTheme( 1843): 2 : Different view - status_min_formatted : 33 != 34
D/WeatherTheme( 1843): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
,D/WeatherTheme( 1843): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1843): 2 : Fixed theme : optimus
,D/WeatherTheme( 1843): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherService( 1843): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 1:34:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2029): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  961): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  961): [updateScreenState] screen on = false
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  961): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8473 usec
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  961): hal_acquire_resources
,I/qcom_sensors_hal(  961): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  961): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  961): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  961): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  961): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  961): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  961): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.458771 Y: -0.403015 Z: 9.757874 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458771 .y:-0.403015 .z:9.757874
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.456635 Y: -0.409668 Z: 9.775406 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456635 .y:-0.409668 .z:9.775406
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Sensors (  469): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  961): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  961): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  961): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  961): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  961): proximitySensorChanged  positive = true
I/KnockOnPowerController(  961): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.467575 Y: -0.404587 Z: 9.777863 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467575 .y:-0.404587 .z:9.777863
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.456879 Y: -0.402557 Z: 9.768539 
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.452423 Y: -0.403671 Z: 9.769638 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.456879 .y:-0.402557 .z:9.768539
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.462143 Y: -0.401520 Z: 9.763138 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462143 .y:-0.401520 .z:9.763138
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.464111 Y: -0.410324 Z: 9.759476 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464111 .y:-0.410324 .z:9.759476
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  961): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44797120)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  961): **** SHOWN CALLED ****
I/WindowManager(  961): No lock screen! windowToken=null
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.465225 Y: -0.401993 Z: 9.775391 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465225 .y:-0.401993 .z:9.775391
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  275): Screen released, type=0 flinger=0xb8d6f450
,D/qdhwcomposer(  275): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  961): handleScreenStateChanged: true
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2029): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  961): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  961): stopMonitoring
,D/wpa_supplicant( 2029): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131127
D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=132097
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  961): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2029): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2029): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  961): handleMessage: X
E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 961
,V/SRS_Proc(  278): ParamSet string: screen_state=on
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4384e350 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1843): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:34:4
,E/SlideAside( 3999): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3999): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1843): 2 : This is isUpdating : false
,D/WeatherAncestor( 1843): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:34:4
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1843): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1843): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1843): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1843): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255,
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
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
,D/qdlights( 1156): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1156): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 243, B = 243
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 237, B = 237
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  275): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  961): Excessive delay in blankDisplay() while turning screen off: 430ms
D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658044722, nextTick: 55309, mDrawingTime: 2
D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658044740, nextTick: 55293, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/WeatherService( 1843): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:34:4
D/WeatherService( 1843): 2 : ACTION screen on
,D/WeatherService( 1843): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1843): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:34:4
D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): Emergency Service
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_ON
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
,V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
D/qcom_sensors_hal(  961): hal_acquire_resources
D/qcom_sensors_hal(  961): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  961): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.469086 Y: -0.396301 Z: 9.776428 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469086 .y:-0.396301 .z:9.776428
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  961): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  961): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  961): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
,D/KeyguardViewManager( 1142): onScreenTurnedOff()
,I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{4313d840 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/LGImmersionVibrator(  961): Vibrator off
D/WifiStateMachine(  961): handleScreenStateChanged: false
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  961): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 961
V/SRS_Proc(  278): ParamSet string: screen_state=off
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  278): adev_set_parameters: exit with code(-2)
D/WifiController(  961): CMD_SCREEN_OFF 
,D/WifiController(  961): shouldWifiStayAwake TRUE
D/wpa_supplicant( 2029): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2029): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1156): clear
,D/wpa_supplicant( 2029): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
,D/WifiNative-wlan0(  961):    returned true
,D/WifiStateMachine(  961): handleMessage: X
,D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
E/Parcel  (  522): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
D/WeatherService( 1843): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:34:4
D/WeatherService( 1843): 2 : ACTION screen off
,D/WeatherService( 1843): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:34:4
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1475): NFC-C OFF
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1156): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1156): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1156): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1156): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1156): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1156): set_light_notifications: 2,ff002d2d,10,0,2
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
,I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1156): GC_CONCURRENT freed 2900K, 11% free 25451K/28528K, paused 38ms+2ms, total 89ms
,I/Sensors (  469): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  291): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658052880130637; DSPS: 4952717; Offset: 1450657901735202659
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  961): GC_EXPLICIT freed 2948K, 47% free 30677K/57552K, paused 4ms+10ms, total 135ms
,D/Diskstats( 1969): User is not opted-in to Usage & Diagnostics.
,D/Procstats( 1969): User is not opted-in to Usage & Diagnostics.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658072881993231; DSPS: 5608138; Offset: 1450657901735203681
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/VacuumService( 1535): Vacuum at: now=1450658075043 tag=VacuumService
,I/GoogleURLConnFactory( 1535): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1535): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1535): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1535): GC_CONCURRENT freed 1808K, 28% free 18038K/24832K, paused 2ms+6ms, total 44ms
,W/Uploader( 1535): No account for auth token provided
,W/Uploader( 1535):  no longer exists, so no auth token.
,W/Uploader( 1535): No account for auth token provided
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658092884173806; DSPS: 6263569; Offset: 1450657901735217508
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658100037, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658100044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658112885087515; DSPS: 6918959; Offset: 1450657901735215689
,D/wpa_supplicant( 2029): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658132885497480; DSPS: 7574332; Offset: 1450657901735228926
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658152886752097; DSPS: 8229734; Offset: 1450657901735201805
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658160048, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658160055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658172887178426; DSPS: 8885107; Offset: 1450657901735231405
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658192888036823; DSPS: 9540496; Offset: 1450657901735204792
,D/wpa_supplicant( 2029): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 6 BSSID 8c:04:ff:b9:af:25 SSID 'SALVADOR' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 7 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 8 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 9 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 10 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2029): wlan0: BSS: Remove id 11 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2029): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 8c:04:ff:b9:af:25]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 a0:c5:62:7a:49:96]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ab]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 fc:94:e3:11:35:3a]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 fe:94:e3:11:35:3c]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658212889144472; DSPS: 10195892; Offset: 1450657901735213808
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658220036, nextTick: 59983, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658220045, nextTick: 59987, mDrawingTime: 0
,D/dalvikvm( 2673): GC_CONCURRENT freed 7726K, 32% free 16927K/24832K, paused 3ms+2ms, total 37ms
,D/dalvikvm( 2673): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658232889581554; DSPS: 10851266; Offset: 1450657901735223644
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x436f4370: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1535): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1535): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1535): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1535): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1535): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1535): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1535): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1535): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4185): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4185): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4185): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4185): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4185): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4185): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4185): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4185): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4185): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4185): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  961): remove 4383ebe0
D/LocationManagerService(  961): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2673): GC_CONCURRENT freed 1929K, 32% free 16959K/24832K, paused 9ms+2ms, total 37ms
,D/dalvikvm( 2673): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2673): GC_CONCURRENT freed 1473K, 30% free 17534K/24832K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 2673): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/Mlt MonitorService( 2673): parseLastkmsg to dump
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658252891466817; DSPS: 11506688; Offset: 1450657901735216817
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658272891892472; DSPS: 12162062; Offset: 1450657901735215226
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658280035, nextTick: 59970, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658280055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658292892782271; DSPS: 12817451; Offset: 1450657901735220016
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658312893220150; DSPS: 13472825; Offset: 1450657901735230649
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658332894097887; DSPS: 14128214; Offset: 1450657901735223376
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658340031, nextTick: 59991, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658340044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658352894556681; DSPS: 14783589; Offset: 1450657901735224406
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658372894988853; DSPS: 15438964; Offset: 1450657901735198814
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658392895420286; DSPS: 16094338; Offset: 1450657901735203001
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658400027, nextTick: 59979, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658400055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658412895869371; DSPS: 16749712; Offset: 1450657901735224840
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658432896737969; DSPS: 17405101; Offset: 1450657901735208428
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658452897158611; DSPS: 18060475; Offset: 1450657901735201824
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658460030, nextTick: 59992, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658460055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658472897608975; DSPS: 18715849; Offset: 1450657901735224942
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658492898496007; DSPS: 19371238; Offset: 1450657901735226965
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658512899353072; DSPS: 20026627; Offset: 1450657901735199020
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658520036, nextTick: 59985, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658520043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658532899806818; DSPS: 20682001; Offset: 1450657901735225520
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658552900246292; DSPS: 21337376; Offset: 1450657901735207230
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658572902493962; DSPS: 21992810; Offset: 1450657901735196599
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658580033, nextTick: 59985, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658580042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658592902944194; DSPS: 22648184; Offset: 1450657901735219585
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658612903836835; DSPS: 23303574; Offset: 1450657901735196699
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658632904691232; DSPS: 23958962; Offset: 1450657901735196604
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658640032, nextTick: 59995, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658640045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658652905113322; DSPS: 24614335; Offset: 1450657901735221965
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658672905578130; DSPS: 25269711; Offset: 1450657901735198492
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658692906023177; DSPS: 25925085; Offset: 1450657901735216293
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658700054, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658700055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658712907395244; DSPS: 26580490; Offset: 1450657901735215069
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658732907824021; DSPS: 27235864; Offset: 1450657901735216600
,D/Finsky  ( 4185): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  961): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  961): Done.
,D/QcConnectivityService(  961): Setting timer for 720seconds
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4185): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4185): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4185): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4185): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4185): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4185): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DeviceConnectionService( 1425): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658752908282497; DSPS: 27891239; Offset: 1450657901735217312
,D/Finsky  ( 4185): [393] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4185): [1] 5.onFinished: Installation state replication succeeded.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658760053, nextTick: 59978, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658760054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658772911519920; DSPS: 28546705; Offset: 1450657901735219872
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658792912817940; DSPS: 29202108; Offset: 1450657901735205636
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658812913709866; DSPS: 29857497; Offset: 1450657901735212552
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658820063, nextTick: 59968, mDrawingTime: 1
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658820064, nextTick: 59968, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658832915064850; DSPS: 30512902; Offset: 1450657901735194245
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658852915929125; DSPS: 31168290; Offset: 1450657901735204028
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658872916810819; DSPS: 31823679; Offset: 1450657901735200712
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658880033, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658880041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658892918238460; DSPS: 32479086; Offset: 1450657901735194027
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658912919514213; DSPS: 33134487; Offset: 1450657901735218559
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658932920999179; DSPS: 33789896; Offset: 1450657901735208164
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658940031, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450658940041, nextTick: 59991, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658952922434544; DSPS: 34445303; Offset: 1450657901735209203
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658972923299401; DSPS: 35100691; Offset: 1450657901735219568
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450658992924146204; DSPS: 35756079; Offset: 1450657901735211878
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659000032, nextTick: 59976, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659000049, nextTick: 59978, mDrawingTime: 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659012925504177; DSPS: 36411484; Offset: 1450657901735196560
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659032926850391; DSPS: 37066888; Offset: 1450657901735200001
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659052927692890; DSPS: 37722275; Offset: 1450657901735218525
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659060044, nextTick: 59969, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659060055, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659072929036302; DSPS: 38377680; Offset: 1450657901735188646
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659092929894871; DSPS: 39033068; Offset: 1450657901735192723
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659112931398254; DSPS: 39688477; Offset: 1450657901735200745
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659120044, nextTick: 59981, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659120046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659132932791879; DSPS: 40343882; Offset: 1450657901735221079
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659152933658522; DSPS: 40999271; Offset: 1450657901735202712
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659172934519381; DSPS: 41654659; Offset: 1450657901735209079
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659180053, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659180054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659192935905912; DSPS: 42310064; Offset: 1450657901735222319
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659212936326782; DSPS: 42965438; Offset: 1450657901735215943
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659232937255508; DSPS: 43620829; Offset: 1450657901735198624
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659240063, nextTick: 59967, mDrawingTime: 2
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659240064, nextTick: 59968, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659252938602636; DSPS: 44276233; Offset: 1450657901735202978
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659272939444703; DSPS: 44931620; Offset: 1450657901735221071
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659292940288072; DSPS: 45587008; Offset: 1450657901735209947
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659300052, nextTick: 59979, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659300054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659312941704392; DSPS: 46242415; Offset: 1450657901735191941
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659332942548776; DSPS: 46897802; Offset: 1450657901735212351
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659352943418330; DSPS: 47553191; Offset: 1450657901735196895
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659360042, nextTick: 59988, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659360045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659372944847163; DSPS: 48208597; Offset: 1450657901735221919
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659392945706261; DSPS: 48863985; Offset: 1450657901735226525
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659412946971216; DSPS: 49519387; Offset: 1450657901735209742
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659420052, nextTick: 59979, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659420054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659432948359779; DSPS: 50174792; Offset: 1450657901735225014
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659452949272660; DSPS: 50830182; Offset: 1450657901735222368
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  961): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  961): Done.
,D/QcConnectivityService(  961): Setting timer for 720seconds
,I/EventLogService( 1969): Aggregate from 1450658023601 (log), 1450657572110 (data)
,D/GCM     ( 1535): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659472950157193; DSPS: 51485571; Offset: 1450657901735221891
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659480042, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659480045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659492952084206; DSPS: 52140995; Offset: 1450657901735195779
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659512952984213; DSPS: 52796384; Offset: 1450657901735210776,
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659532954234696; DSPS: 53451785; Offset: 1450657901735210038
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659540037, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659540053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659552955586210; DSPS: 54107189; Offset: 1450657901735218779
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659572956008299; DSPS: 54762563; Offset: 1450657901735213622
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659592956895247; DSPS: 55417952; Offset: 1450657901735215560
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659600047, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659600054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659612958281316; DSPS: 56073358; Offset: 1450657901735197820
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659632959142675; DSPS: 56728746; Offset: 1450657901735204687
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659652960034924; DSPS: 57384135; Offset: 1450657901735211926
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659660041, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659660044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659672962075074; DSPS: 58039562; Offset: 1450657901735207399
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659692962510734; DSPS: 58694936; Offset: 1450657901735215813
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659712963401768; DSPS: 59350325; Offset: 1450657901735221837
,I/ProcessStatsService(  961): Prepared write state in 45ms
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659720073, nextTick: 59957, mDrawingTime: 2
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659720075, nextTick: 59958, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  961): Pruning old procstats: /data/system/procstats/state-2015-12-20-04-12-14.bin
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1535): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1535): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1535): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1535): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1535): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1535): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659732964864284; DSPS: 60005733; Offset: 1450657901735219509
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659752966174285; DSPS: 60661136; Offset: 1450657901735217254
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659772966587667; DSPS: 61316510; Offset: 1450657901735203390
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659780040, nextTick: 59974, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450659780052, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659792967734897; DSPS: 61971907; Offset: 1450657901735221470
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450659812968681713; DSPS: 62627298; Offset: 1450657901735222241
,TIME-OUT KILL (timeout was 1800000ms)
```
