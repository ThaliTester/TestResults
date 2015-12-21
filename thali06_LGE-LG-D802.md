#### Test 54312298c831015_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1960): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1960): launchTask
W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1960): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1960): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1960): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XkPx3siq4xnNUsTiReAEj8CVJkSqiwMp8Q3tNKKv4_WEV5-MHzZwkWwacxhxcthApUyyqBr2Xjxghnj3RFYlJtjdlyniH3ksaKXtl_4WgPUZJeBMo0I3MNMrQbieh5muxD9sC7cw_pICN2A_F8Q-lzjSCynwZ37bUR0pndu0tEucZ9i6j_zXsuVTaAKs6ukquFV9Vq
I/GoogleURLConnFactory( 1960): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1960): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1960): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1960): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1960): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1960): Using Auth Proxy for data requests.
W/BaseAppContext( 1960): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1960): CP2 sync disabled
I/dalvikvm( 1960): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1960): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1960): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1960): Using Auth Proxy for data requests.
W/BaseAppContext( 1960): Using Auth Proxy for data requests.
W/BaseAppContext( 1960): Using Auth Proxy for data requests.
W/BaseAppContext( 1960): Using Auth Proxy for data requests.
W/GAV2    ( 4614): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 3950:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1960): fetch service done; releasing wakelock
I/ConfigFetchService( 1960): stopping self
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 1960): GC_CONCURRENT freed 1531K, 22% free 19469K/24832K, paused 3ms+8ms, total 44ms
D/ChimeraCfgMgr( 1960): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1960): Module APK com.google.android.play.games already loaded
I/Icing   ( 1960): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1960): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1960): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2012): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4676): 
D/AndroidRuntime( 4676): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4676): CheckJNI is OFF
D/dalvikvm( 4676): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4676): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4676): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4676): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4676): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4676): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4676): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4676): failed to load memtrack module: -2
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/AndroidRuntime( 4676): Calling main entry com.android.commands.am.Am
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4676
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (108 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{43529ce0 stackId=1, 2 tasks}
I/ActivityManager(  966): startService SlideAside
D/AndroidRuntime( 4676): Shutting down VM
I/SlideAside( 3706): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4676): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 3ms
I/SlideAside( 3706): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/UsbSettingsControl( 2602): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2602): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/SlideAside( 3706): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2} state=PAUSING
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4693 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4693): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4693): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4693): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4693): Binding Chromium to the background looper Looper (main, tid 1) {42ac5010}
I/chromium( 4693): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4693): Initializing chromium process, renderers=0
W/chromium( 4693): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4693): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4693): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4693): Remote Branch: 
I/Adreno-EGL( 4693): Local Patches: 
I/Adreno-EGL( 4693): Reconstruct Branch: 
I/dalvikvm( 4693): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4693): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4693): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4693): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4693): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4693): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4693): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4693): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4693): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4693): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4693): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4693): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4693): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4693): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4693): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4693): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4693): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4693): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4693): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4693): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4693): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4693): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4693): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4693): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4693): Enabling debug mode 0
,W/AwContents( 4693): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  966): IME STATUS OFF
W/AwContents( 4693): nativeOnDraw failed; clearing to background color.
,I/ActivityManager( 4693): Timeline: Activity_idle id: android.os.BinderProxy@42ac6ca8 time:112676
,I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +449ms
,D/JsMessageQueue( 4693): Set native->JS mode to OnlineEventsBridgeMode
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.464981 Y: -0.395538 Z: 9.756287 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464981 .y:-0.395538 .z:9.756287
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/dalvikvm( 4693): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42aca9b0
D/dalvikvm( 4693): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42aca9b0
D/jxcore_app_log( 4693): JniHelper::setJavaVM(0x41a72808), pthread_self() = 1640379152
D/JX-Cordova( 4693): jxcore cordova android initializing
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.455109 Y: -0.397263 Z: 9.768417 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455109 .y:-0.397263 .z:9.768417
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3} time:113001
D/ActivityManager(  966): no-history finish of ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{42e342d8 ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2602): [AUTORUN] onStop()
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 4693): GC_CONCURRENT freed 2754K, 12% free 21865K/24832K, paused 2ms+2ms, total 38ms
D/dalvikvm( 4693): GC_FOR_ALLOC freed 244K, 13% free 21830K/24832K, paused 22ms, total 22ms
D/dalvikvm( 4693): GC_FOR_ALLOC freed 187K, 12% free 21855K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4693): Grow heap (frag case) to 23.655MB for 144892-byte allocation
D/dalvikvm( 4693): GC_FOR_ALLOC freed 253K, 13% free 21903K/24976K, paused 22ms, total 22ms
I/dalvikvm-heap( 4693): Grow heap (frag case) to 23.770MB for 217334-byte allocation
D/dalvikvm( 4693): GC_FOR_ALLOC freed 369K, 13% free 21978K/25192K, paused 22ms, total 22ms
I/dalvikvm-heap( 4693): Grow heap (frag case) to 23.947MB for 325996-byte allocation
D/dalvikvm( 4693): GC_FOR_ALLOC freed 568K, 14% free 22099K/25512K, paused 22ms, total 22ms
I/dalvikvm-heap( 4693): Grow heap (frag case) to 24.221MB for 488990-byte allocation
D/dalvikvm( 4693): GC_FOR_ALLOC freed 867K, 15% free 22276K/25992K, paused 22ms, total 22ms
I/dalvikvm-heap( 4693): Grow heap (frag case) to 24.627MB for 733480-byte allocation
,D/dalvikvm( 4693): GC_FOR_ALLOC freed 1284K, 16% free 22533K/26712K, paused 23ms, total 23ms
,D/dalvikvm( 4693): GC_CONCURRENT freed 1674K, 15% free 22906K/26712K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 4693): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4693): GC_FOR_ALLOC freed 368K, 15% free 22862K/26712K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4693): Grow heap (frag case) to 26.074MB for 1650320-byte allocation
,D/dalvikvm( 4693): GC_CONCURRENT freed 1707K, 18% free 23434K/28324K, paused 2ms+2ms, total 29ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1220): Disconnected process message: 10
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,D/dalvikvm( 4693): GC_FOR_ALLOC freed 1347K, 17% free 23514K/28324K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4693): Grow heap (frag case) to 27.498MB for 2475476-byte allocation
,D/dalvikvm( 4693): GC_CONCURRENT freed 267K, 16% free 26016K/30744K, paused 2ms+3ms, total 49ms
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 4693): GC_FOR_ALLOC freed 4336K, 21% free 24488K/30744K, paused 37ms, total 37ms
,I/dalvikvm-heap( 4693): Grow heap (frag case) to 29.628MB for 3713210-byte allocation
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2012): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/dalvikvm( 4693): GC_CONCURRENT freed 419K, 19% free 27929K/34372K, paused 4ms+6ms, total 51ms
,D/dalvikvm( 4693): GC_FOR_ALLOC freed 3029K, 26% free 25437K/34372K, paused 24ms, total 24ms
,W/jxcore-log( 4693): Initializing JXcore engine
,W/jxcore-log( 4693): JXcore engine is ready
,D/dalvikvm( 4693): GC_CONCURRENT freed 356K, 19% free 28067K/34372K, paused 2ms+2ms, total 44ms
,D/dalvikvm( 4693): WAIT_FOR_CONCURRENT_GC blocked 41ms
,W/jxcore-log( 4693): Starting JXcore engine
,W/jxcore-log( 4693): Platform android
W/jxcore-log( 4693): 
,W/jxcore-log( 4693): Process ARCH arm
W/jxcore-log( 4693): 
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Clock   ( 1140): Clock updated, drawingStartTime : 1450738920031, nextTick: 60000, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450738920056, nextTick: 59977, mDrawingTime: 0
,I/ActivityManager(  966): Killing 4142:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
,I/jxcore-log( 4693): JXcore Cordova bridge is ready!
I/jxcore-log( 4693): 
,W/jxcore-log( 4693): JXcore engine is started
,I/chromium( 4693): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 4614): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1559): onDestroy
,I/jxcore-log( 4693): Toggling radios to true
I/jxcore-log( 4693): 
,D/BluetoothManagerService(  966): Message: 20
,D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44c3b9e8:true
,D/BluetoothAdapter( 4693): enable(): BT is already enabled..!
D/WifiService(  966): New client listening to asynchronous messages
D/WifiService(  966): setWifiEnabled: true pid=4693, uid=10304
E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  966): setWifiEnabled startWifiDelaySendMsg true
,D/WifiStateMachine(  966): handleMessage: E msg.what=131145
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doBoolean: DISCONNECT
,I/jxcore-log( 4693): Radios toggled
I/jxcore-log( 4693): 
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2012): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2012): wlan0: Cancelling scan request
D/wpa_supplicant( 2012): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2012): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2012): TDLS: Tear down peers
,D/wpa_supplicant( 2012): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4693): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4693): 
,I/jxcore-log( 4693): Perf Test app loaded loaded
I/jxcore-log( 4693): 
D/WifiService(  966): disconnect pid=4693, uid=10304
D/WifiService(  966): reconnect pid=4693, uid=10304
,D/wpa_supplicant( 2012): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2012): wlan0: Deauthentication notification
D/wpa_supplicant( 2012): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2012): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2012): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2012): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2012): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2012): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb75b1d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2012):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2012): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2012): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2012): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2012): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2012): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2012): nl80211: Event message available
D/wpa_supplicant( 2012): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received, for wlan0
D/wpa_supplicant( 2012): nl80211: Ignore disconnect event triggered during reassociation
D/wpa_supplicant( 2012): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2012): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/jxcore-log( 4693): check test folder
I/jxcore-log( 4693): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
I/jxcore-log( 4693): found test : ./testFindPeers.js
I/jxcore-log( 4693): 
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  966): invokeExitMethods: ConnectedState
W/Settings(  966): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  966): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  966): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131146
D/WifiStateMachine(  966): processMsg: DisconnectingState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiNative-wlan0(  966): doBoolean: RECONNECT
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2012): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2012): Fast associate: Old scan results
D/wpa_supplicant( 2012): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2012): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2012): wlan0: nl80211: scan request
D/wpa_supplicant( 2012): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2012): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2012): nl80211: Event message available
D/wpa_supplicant( 2012): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2012): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147460
D/WifiStateMachine(  966): processMsg: DisconnectingState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): Network connection lost
D/WifiStateMachine(  966): Stopping DHCP and clearing IP
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  966): doBoolean: SET ps 1
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2012): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2012): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2012): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
,D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2012): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2012): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  966):    returned true
,D/DhcpStateMachine(  966): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  966): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  966): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  966): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
D/QCNEA   (  404): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  404): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  404): |CAC| updateNetCfgInfo
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC|                   Netconfig               
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  404): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  404): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  404): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  404): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  404): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  404): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| Received bssid= 
D/QCNEA   (  404): |CAC| net type = 3
V/QCNEA   (  404): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  404): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  404): |CAC| 	ssid           =NG700
V/QCNEA   (  404): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  404): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  404): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  404): |CAC| dispatchNetCfg: updating:0xb82218dc
,D/QCNEA   (  404): |CAC| readCallback: read len:0, ret:-1, errno:11
I/jxcore-log( 4693): found test : ./testSendData.js
I/jxcore-log( 4693): 
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  966): hidePasspointNotification off =false
D/QcConnectivityService(  966): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  966): Attempting to switch to mobile
D/QcConnectivityService(  966): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  966): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  966): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  966): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  966): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131213
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131213
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  966): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 20ms
,I/ActivityManager(  966): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4744 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  264): RouteController
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/jxcore-log( 4693): found test : ./testSendData2.js
I/jxcore-log( 4693): 
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 21ms
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,E/jxcore  ( 4693): Error!: missing ) after argument list
E/jxcore  ( 4693): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/Choreographer( 4693): Skipped 70 frames!  The application may be doing too much work on its main thread.
W/NetworkManagementService(  966): route cmd failed: 
W/NetworkManagementService(  966): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  966): '
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  966): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  966): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  966): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  966): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  966): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  966): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  966): android_net_utils_resetConnections in env=0x61832f58 clazz=0x6c500001 iface=wlan0 mask=0x3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  966): resetConnections(wlan0, 3)
,V/NativeCrypto( 1559): Read error: ssl=0x63a854f0: I/O error during system call, Connection timed out
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 21ms
,V/NativeCrypto( 1559): SSL shutdown failed: ssl=0x63a854f0: I/O error during system call, Broken pipe
,I/chromium( 4693): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/HyLog   ( 4744): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4744): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4744): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/chromium( 4693): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  966): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  966): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,I/PCSuite ( 4744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4744): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  966): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4782 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  966): Killing 2134:android.process.media/u0a23 (adj 15): empty #17
,I/chromium( 4693): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4782): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4782): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4782): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4782): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4782): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4782): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/DhcpStateMachine(  966): StoppedState
,D/QRemote ( 4782): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4782): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4782): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4782): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  966): Killing 3861:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: DisconnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): processMsg: DriverStartedState
,D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
,D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1220): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] connect :false
D/wpa_supplicant( 2012): nl80211: Event message available
D/wpa_supplicant( 2012): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2012): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2012): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2012): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 2012): nl80211: Survey data missing
D/wpa_supplicant( 2012): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2012): wlan0: BSS: Add new id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: BSS: Add new id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: BSS: Add new id 7 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 2012): wlan0: New scan results available
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2012): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2012): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2012): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2012): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2012): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2012): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2012): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2012): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2012): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2012): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2012): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2012): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2012): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-62 wps
D/wpa_supplicant( 2012): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2012): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2012): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2012): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2012): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2012): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2012): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2012): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2012): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb75b35a8  current_ssid=0x0
D/wpa_supplicant( 2012): scard is not null..
D/wpa_supplicant( 2012): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2012): wpa_supplicant_check_m,dm_ac_policy policy: 0
D/wpa_supplicant( 2012): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2012): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2012): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2012): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2012): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2012): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2012): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2012): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2012): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2012): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2012): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2012): wlan0: Cancelling scan request
D/wpa_supplicant( 2012): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2012): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2012): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2012): RSN: PMKSA cache search - network_ctx=0xb75b35a8 try_opportunistic=0
D/wpa_supplicant( 2012): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): RSN: No PMKSA cache entry found,
,D/wpa_supplicant( 2012): wlan0: RSN: using IEEE 802.11i/D9.0,
D/wpa_supplicant( 2012): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2012): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2012): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2012): wlan0: WPA: using GTK CCMP
,D/wpa_supplicant( 2012): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2012): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2012): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2012): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2012): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 2012): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2012): wlan0: State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 2012): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2012): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0),
,D/wpa_supplicant( 2012): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2012): nl80211: Unsubscribe mgmt frames handle 0xb75b2590 (mode change)
D/wpa_supplicant( 2012): nl80211: Subscribe to mgmt frames with non-AP handle 0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=2): 04 0a,
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
,D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
,D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
,D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=2): 0a 07,
D/wpa_supplicant( 2012): nl80211: Register frame type=0xd0 nl_handle=0xb75b2590
D/wpa_supplicant( 2012): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2012): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2012):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2012):   * freq=2412
D/wpa_supplicant( 2012):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2012):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2012):   * Auth Type 0
,D/wpa_supplicant( 2012):   * WPA Versions 0x2,
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 c2:ff:d4:d3:aa:48]
D/wpa_supplicant( 2012): nl80211: Connect request send successfully,
D/wpa_supplicant( 2012): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2012): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): EAPOL: External notification - EAP fail=0,
,D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2012): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2012): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2012): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:97]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 64:7c:34:38:27:cc],
D/WifiMonitor(  966): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  966): couldn't identify event type - WPS-AP-AVAILABLE ,
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  966): handleMessage: E msg.what=147461
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState,
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt,
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  966): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2012): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/wpa_supplicant( 2012): nl80211: Event message available
D/wpa_supplicant( 2012): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2012): nl80211: Connect event
D/wpa_supplicant( 2012): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2012): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2012): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2012): wlan0: Association info event
D/wpa_supplicant( 2012): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2012): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2012): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2012): wlan0: freq=2412 MHz
D/wpa_supplicant( 2012): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2012): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2012): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2012): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2012): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2012): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): scard is not null..
D/wpa_supplicant( 2012): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2012): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2012): TDLS: Remove peers on association
D/wpa_supplicant( 2012): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2012): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2012): EAPOL: enable timer tick
D/wpa_supplicant( 2012): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2012): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2012): wlan0: Cancelling scan request
,D/wpa_supplicant( 2012): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2012): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2012): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2012): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2012): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2012): nl80211: if_removed already cleared - ignore event,
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  966): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
,D/WifiStateMachine(  966): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
D/wpa_supplicant( 2012): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 78 92 fb 67 8f 2b 38 96 ea 91 c2 6d 1f 57 07 ...
D/wpa_supplicant( 2012): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2012): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2012): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2012): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2012): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2012):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2012):   key_nonce - hexdump(len=32): 78 92 fb 67 8f 2b 38 96 ea 91 c2 6d 1f 57 07 cc b1 ad a2 ef 10 7f 07 00 67 43 a7 ab 31 a4 39 e0
D/wpa_supplicant( 2012):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 78 92 fb 67 8f 2b 38 96 ea 91 c2 6d 1f 57 07 ...
D/wpa_supplicant( 2012): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2012): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2012): Get randomness: len=32 entropy=8
D/wpa_supplicant( 2012): WPA: Renewed SNonce - hexdump(len=32): cb 7d b1 0e 41 16 ed 2f 9b 54 0b d5 ff c7 07 bc cf 60 fc e0 31 74 6c c0 61 d0 68 f8 9e a1 bf 8c
D/wpa_supplicant( 2012): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): WPA: Nonce1 - hexdump(len=32): cb 7d b1 0e 41 16 ed 2f 9b 54 0b d5 ff c7 07 bc cf 60 fc e0 31 74 6c c0 61 d0 68 f8 9e a1 bf 8c
D/wpa_supplicant( 2012): WPA: Nonce2 - hexdump(len=32): 78 92 fb 67 8f 2b 38 96 ea 91 c2 6d 1f 57 07 cc b1 ad a2 ef 10 7f 07 00 67 43 a7 ab 31 a4 39 e0
D/wpa_supplicant( 2012): WPA: PMK - hexdump(len=32): [REMOVED]
,D/wpa_supplicant( 2012): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2012): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2012): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2012): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2012): WPA: KCK - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 2012): WPA: Derived Key MIC - hexdump(len=16): 9e f3 91 d3 07 20 89 e3 7a e7 2e 1d bd f7 e2 2d
D/wpa_supplicant( 2012): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 cb 7d b1 0e 41 16 ed 2f 9b 54 0b d5 ff c7 07 ...
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
,D/WifiStateMachine(  966): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/wpa_supplicant( 2012): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 78 92 fb 67 8f 2b 38 96 ea 91 c2 6d 1f 57 07 ...
D/wpa_supplicant( 2012): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2012): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2012): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2012): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2012):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2012):   key_nonce - hexdump(len=32): 78 92 fb 67 8f 2b 38 96 ea 91 c2 6d 1f 57 07 cc b1 ad a2 ef 10 7f 07 00 67 43 a7 ab 31 a4 39 e0
D/wpa_supplicant( 2012):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012):   key_rsc - hexdump(len=8): b3 61 00 00 00 00 00 00
D/wpa_supplicant( 2012):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2012):   key_mic - hexdump(len=16): 35 94 54 c7 c0 af bf 5a 67 96 da 54 78 59 43 58
D/wpa_supplicant( 2012): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 78 92 fb 67 8f 2b 38 96 ea 91 c2 6d 1f 57 07 ...
D/wpa_supplicant( 2012): RSN: encrypted key data - hexdump(len=56): 78 4e 11 a8 74 6b 15 27 88 c6 cd 7f ba ee 62 9e e4 50 68 92 a5 e9 31 7e 99 50 94 3a d6 9a 24 49 ...
D/wpa_supplicant( 2012): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2012): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2012): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2012): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 81 f8 ...
D/wpa_supplicant( 2012): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2012): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2012): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2012): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2012): WPA: Derived Key MIC - hexdump(len=16): 74 b3 c9 39 c9 99 2d 92 66 9e fd be c3 28 ad fd
,D/wpa_supplicant( 2012): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 2012): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb75b2c54 key_idx=0 set_tx=1 seq_len=6 key_len=16,
,D/wpa_supplicant( 2012):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2012): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2012): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED],
D/wpa_supplicant( 2012): WPA: Group Key - hexdump(len=16): [REMOVED],
,D/wpa_supplicant( 2012): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2012): WPA: RSC - hexdump(len=6): b3 61 00 00 00 00
,D/wpa_supplicant( 2012): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f7503a key_idx=2 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 2012):    broadcast key
I/wpa_supplicant( 2012): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2012): wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
I/wpa_supplicant( 2012): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2012): netlink: Operstate: linkmode=-1, operstate=6
,D/wpa_supplicant( 2012): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2012): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): EAPOL: External notification - portValid=1,
,D/wpa_supplicant( 2012): EAPOL: External notification - EAP success=1,
D/wpa_supplicant( 2012): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2012): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2012): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2012): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 2012): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2012): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2012): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2012): EAPOL authentication completed successfully
D/wpa_supplicant( 2012): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 2012): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2012): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
,D/WifiMonitor(  966): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,W/WifiMonitor(  966): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147459
D/WifiStateMachine(  966): processMsg: DisconnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): Network connection established
,D/WifiNative-wlan0(  966): doString: STATUS
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2012): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  966):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  966): ssid=NG700
D/WifiNative-wlan0(  966): id=0
D/WifiNative-wlan0(  966): mode=station
D/WifiNative-wlan0(  966): pairwise_cipher=CCMP
D/WifiNative-wlan0(  966): group_cipher=CCMP
D/WifiNative-wlan0(  966): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  966): wpa_state=COMPLETED
D/WifiNative-wlan0(  966): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  966): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  966): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  966): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  966): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  966): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  966): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=5
,D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
,I/AppUp4:CustModeStarterReceiver( 4005): onReceive
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  966): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  966): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  966): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  966): WaitBeforeStartState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
,D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-51ms what=147462 obj=android.net.wifi.StateChangeResult@451bd2e8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/AppUp4:CustFacade( 4005): Context : android.app.ReceiverRestrictedContext@42ad80f0
D/AppUp4:CustFacade( 4005): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4005): isOpenOperator : true
D/AppUp4:CustFacade( 4005): isPhone : true
,D/WifiStateMachine(  966): handleMessage: X
,I/LicenseContentProvider( 2975): start selecting data
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/SIMObserver( 2975): simInfo1
D/WifiStateMachine(  966): handleMessage: E msg.what=147462
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-48ms what=147462 obj=android.net.wifi.StateChangeResult@43f45a28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=147459
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-48ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-9ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
I/AppUp4:EulaManager( 4005): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4005): begin check event
I/AppUp4:CustModeStarterReceiver( 4005): Event For GoodConnectivity
D/wpa_supplicant( 2012): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=196612
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-16ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2012): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/ActivityManager(  966): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4823 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4823): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4823): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4823): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2012): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  966): doBoolean: SET ps 0
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2012): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2012): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2012): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
,D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2012): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2012): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  966):    returned null
E/WifiStateMachine(  966): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  966): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2012): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2012): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  966):    returned null
D/DhcpStateMachine(  966): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  966): DHCP Start wake lock is acquired.
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@435f8080 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@435f8080 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  966): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  966): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  966): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131212
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=196613
D/WifiStateMachine(  966): processMsg: ObtainingIpState
D/WifiStateMachine(  966): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  966): doBoolean: SET ps 1
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2012): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2012): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2012): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  966):    returned true
D/WifiNative-wlan0(  966): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2012): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2012): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): DHCP successful
D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  966): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  966): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState enter
D/WifiStateMachine(  966): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  966): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  966): send additional Connectivity Action
,W/WifiStateTracker(  966): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  966): 
W/WifiStateTracker(  966):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  966):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
D/WifiStateMachine(  966): handleMessage: E msg.what=135190
D/WifiStateMachine(  966): processMsg: VerifyingLinkState
D/WifiStateMachine(  966): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  966): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/Parcel  (  404): Reading a NULL string not supported here.
D/WifiStateMachine(  966): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  966): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  966): CaptivePortalCheckState enter
D/WifiStateMachine(  966): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/WifiStateMachine(  966): handleMessage: X
D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  966): handleMessage: E msg.what=131092
D/WifiStateMachine(  966): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  966): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/QcConnectivityService(  966): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  966): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiStateMachine(  966): transitionTo: destState=ConnectedState
D/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  966): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  966): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1220): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  966): battery changed pluggedType: 2
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  966): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  966): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  404): Reading a NULL string not supported here.
V/DownloadManager( 4823): DownloadService onCreate
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
,D/EAS     ( 4597): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4597): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/ActivityThread(  966): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  966): handleConnectivityChange: preConnState=2 connState=1
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/DownloadManager( 4823): in removeSpuriousFiles
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/        (  264): RouteController
,D/eas_req ( 4597): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4823): DownloadService onStartCommand
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/DownloadManager( 4823): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4330): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4330): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4823): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4330): networkInfo.isConnected() = false
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b01388 on behalf of 4823
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b029b0 on behalf of 4823
,V/        (  264): RouteController
,I/DownloadManager( 4823): in trimDatabase
,V/DownloadManager( 4823): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b044d0 on behalf of 4823
,V/        (  264): RouteController
,I/ActivityManager(  966): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4862 uid=10052 gids={50052, 3003}
V/        (  264): RouteController
V/DownloadManager( 4823): DownloadService onDestroy
V/        (  264): RouteController
,W/linker  ( 4597): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 4597): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4597): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4597): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,V/        (  264): RouteController
,I/dalvikvm( 4597): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4597): register_HtmlEditor, Success
,D/HtmlEditor( 4597): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4597): register_HtmlEditorTimer, Success
D/HtmlEditor( 4597): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4597): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4597): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4597): register_HtmlEditorFont, Success
D/HtmlEditor( 4597): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4597): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4597): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4597): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4597): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
,D/HtmlEditor( 4597): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4597): JNI_OnLoad Success
,I/HubEmail( 4597): JNI_OnLoad()
I/HubEmail( 4597): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4597): registerNatives()
I/HubEmail( 4597): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4597): registerNativeMethods()
,I/HubEmail( 4597): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4597): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  404): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  404): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  404): |CAC| updateNetCfgInfo
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC|                   Netconfig               
V/QCNEA   (  404): |CAC| *********************************************
V/QCNEA   (  404): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  404): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  404): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  404): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  404): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  404): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  404): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  404): |CAC| net type = 1
V/QCNEA   (  404): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  404): |CAC| Received ssid= NG700
V/QCNEA   (  404): |CAC| 	ssid           =NG700
V/QCNEA   (  404): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  404): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  404): |CAC| *********************************************
D/QCNEA   (  404): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  404): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  404): |CAC| dispatchNetCfg: updating:0xb82218dc
D/QCNEA   (  404): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/HyLog   ( 4862): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4862): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4862): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  966): Killing 4301:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
V/LGRssiData( 4862): [loadRssi] File not exist 
V/LGRssiData( 4862): [loadRssi] File not exist 
D/DhcpStateMachine(  966): DHCP request on wlan0
V/TelephonyAutoProfiling( 4862): [loadFeatureFromXml] *** start feature loading from xml
D/LgDhcpStateMachineHelper(  966): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/BaseRuntimeLoader( 4862): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4862): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4862): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4862): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4862): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4862): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4862): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4862): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4862): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4862): onOtaspChanged old =0, new =3
,I/ActivityManager(  966): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4884 uid=10063 gids={50063, 3003, 1028, 1015}
V/PhoneMonitor( 4862): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/CheckinService( 1960): Checking schedule, now: 1450738925299 next: 1450738865730
,I/CheckinService( 1960): active receiver: enabled
,D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1960): Preparing to send checkin request
D/HyLog   ( 4884): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4884): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/EventLogService( 1960): Accumulating logs since 1450738832977
,I/CheckinRequestBuilder( 1960): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1960): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  966): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4905 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  966): Killing 4519:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/HyLog   ( 4905): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4905): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4905): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  966): Killing 4549:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  966): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4931 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4931): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4931): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4931): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  966): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4948 uid=10101 gids={50101, 1028, 1015, 3003}
,D/HyLog   ( 4948): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4948): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4948): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  966): Killing 4582:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,I/NFS     ( 4948): connectivityManager.getNetworkInfo = TYPE_WIFI
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
,I/Wireless_Storage( 4948): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4948): intf.getDisplayName() = lo
,I/Wireless_Storage( 4948): intf.getDisplayName() = sit0
I/Wireless_Storage( 4948): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4948): intf.getDisplayName() = teql0
I/Wireless_Storage( 4948): intf.getDisplayName() = wlan0
,D/NFS     ( 4948): interface name:wlan0 name:wlan0
D/NFS     ( 4948): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4948): interface name:wlan0 name:wlan0
,D/NFS     ( 4948): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4948): CONNECT : WIFI_CONNECT
,D/dalvikvm(  966): GC_EXPLICIT freed 23294K, 49% free 29707K/57504K, paused 3ms+10ms, total 180ms
,I/ActivityManager(  966): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4961 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  966): Killing 4197:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4961): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4961): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4961): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1559): GC_EXPLICIT freed 1004K, 29% free 17811K/24832K, paused 2ms+3ms, total 28ms
,W/GAV2    ( 4961): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DhcpStateMachine(  966): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  966): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  966): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  966): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
,V/LgDhcpStateMachineHelper(  966): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  966): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  966): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  966): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  966): RunningState
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x4349ae88: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1960): awaiting user notification for token
,V/WebViewChromium( 4961): Binding Chromium to the main looper Looper (main, tid 1) {42ac3310}
,I/chromium( 4961): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4961): Initializing chromium process, renderers=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  966): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4985 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4985): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4985): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Adreno-EGL( 4961): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4961): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4961): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4961): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4961): Remote Branch: 
I/Adreno-EGL( 4961): Local Patches: 
I/Adreno-EGL( 4961): Reconstruct Branch: 
,W/dalvikvm( 4985): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4985): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4985): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4985): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4985): VFY: replacing opcode 0x62 at 0x005e
,W/chromium( 4961): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/MultiDex( 4985): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4985): install
,I/MultiDex( 4985): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4985): loading existing secondary dex files
,I/MultiDex( 4985): load found 3 secondary dex files
,I/MultiDex( 4985): install done
,I/NSApplication( 4961): Starting up...
D/dalvikvm( 4985): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4985): VFY: unable to resolve instance field 61
,D/dalvikvm( 4985): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4985): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4985): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4985): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4985): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4985): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4985): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4985): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4985): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4985): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42aca4b8
D/dalvikvm( 4985): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42aca4b8
,D/dalvikvm( 4985): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42aca4b8, skipping init
,D/dalvikvm( 4985): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42aca4b8
D/dalvikvm( 4985): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42aca4b8
,V/JNIHelp ( 4985): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  966): Killing 4211:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4782): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4782): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4782): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4782): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4782): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4782): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4782): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4782): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
D/dalvikvm( 4985): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42aca4b8
D/dalvikvm( 4985): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42aca4b8
D/dalvikvm( 4985): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42aca4b8
,D/dalvikvm( 4985): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42aca4b8
,I/QRemote ( 4782): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4782): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/wpa_supplicant( 2012): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2012): EAPOL: disable timer tick
,I/ProviderInstaller( 4985): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1559): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1559): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1559): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1960): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 1960): Restart initialization of location
,D/WearableService( 1755): callingUid 10006, callindPid: 1755
,E/MDM     ( 1423): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4985): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4985): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4985): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4985): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4985): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4985): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2078000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2078000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=3629677742
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4985): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c9ef60
D/dalvikvm( 4985): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c9ef60
,D/dalvikvm( 4985): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42c9ef60, skipping init
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  966): NetTransition Wakelock for ConnectedState released by timeout
,D/GCM     ( 1559): Connected
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1559): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/WifiStateMachine(  966): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  966): handleMessage: E msg.what=131212
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
D/WifiStateMachine(  966): processMsg: SupplicantStartedState
,D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  966): handleMessage: X
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  966): send additional Connectivity Action
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  966): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/QcConnectivityService(  966): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/LocSvc_java(  966): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  966): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  966): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  966):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  966): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  966): requiresClat: netType=1, hasIPv4Address=true
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=2137020851
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/dalvikvm( 4693): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4693): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4693): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4693): Shutting down VM
,W/dalvikvm( 4693): threadid=1: thread exiting with uncaught exception (group=0x41a83e48)
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/AndroidRuntime( 4693): FATAL EXCEPTION: main
E/AndroidRuntime( 4693): Process: com.test.thalitest, PID: 4693
E/AndroidRuntime( 4693): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4693): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4693): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4693): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4693): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4693): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4693): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4693): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4693): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4693): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4693): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4693): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4693): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4693): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4693): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4693): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4693): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  966):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f}
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4985): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/dalvikvm( 5037): DexOpt: load 2ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 4985): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4985): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 107ms
,I/Adreno-EGL( 4985): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4985): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4985): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4985): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4985): Remote Branch: 
I/Adreno-EGL( 4985): Local Patches: 
I/Adreno-EGL( 4985): Reconstruct Branch: 
,W/Settings( 4985): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4985): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4985): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4985): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4985): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4985): Remote Branch: 
I/Adreno-EGL( 4985): Local Patches: 
I/Adreno-EGL( 4985): Reconstruct Branch: 
,I/Adreno-EGL( 4985): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4985): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4985): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4985): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4985): Remote Branch: 
I/Adreno-EGL( 4985): Local Patches: 
I/Adreno-EGL( 4985): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1960): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,W/ActivityManager(  966): Activity pause timeout for ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{43529ce0 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  966): moveHomeStack:
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1485): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1485): [Launcher.java:717:onResume()]onResume
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1485): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1485): [Launcher.java:868:onResume()]onResume end
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/WeatherAncestor( 1824): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 0:2:7
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1824): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1824): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1824): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1824): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 0:2:7
,D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1824): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1824): 2 : Map key string is -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/lim     ( 1824): 2 : time = 00:02
,I/WeatherReflect( 1824): Model Name : LG-D802
D/WeatherTheme( 1824): 2 : Different view - status_min_formatted : 00 != 02
,D/WeatherTheme( 1824): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1824): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1824): 2 : Fixed theme : optimus
,D/WeatherTheme( 1824): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/CheckinTask( 1960): Sending checkin request (11452 bytes)
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 6521K, 10% free 71474K/78652K, paused 30ms, total 30ms
,D/dalvikvm( 1485): GC_FOR_ALLOC freed 5510K, 9% free 60858K/66608K, paused 19ms, total 19ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1485): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
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
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1485): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1485): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1485): GC_FOR_ALLOC freed 4875K, 9% free 61906K/67476K, paused 20ms, total 20ms
,I/ActivityManager( 1485): Timeline: Activity_idle id: android.os.BinderProxy@42ac0f08 time:122505
,D/UsbSettings( 2602): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2602): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2602): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2602): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{42aea340 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,I/CheckinRequestBuilder( 1960): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1960): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1} time:122552
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1960): awaiting user notification for token
,I/CheckinRequestBuilder( 1960): Classify the device as Phone.
,I/CheckinTask( 1960): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1960): Checking schedule, now: 1450738927799 next: 1451316323797
,I/CheckinService( 1960): active receiver: disabled
,D/dalvikvm(  966): GC_CONCURRENT freed 2203K, 47% free 30819K/57504K, paused 3ms+6ms, total 101ms
D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 98ms
,D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 29ms
D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x42e01d98: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1559): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2012): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4005): onReceive
,D/AppUp4:CustFacade( 4005): Context : android.app.ReceiverRestrictedContext@42ad80f0
D/AppUp4:CustFacade( 4005): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4005): isOpenOperator : true
,D/AppUp4:CustFacade( 4005): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/SIMObserver( 2975): simInfo1
,I/AppUp4:EulaManager( 4005): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4005): begin check event
I/AppUp4:CustModeStarterReceiver( 4005): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4005): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4005): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4005): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4005): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4005): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4597): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
V/DownloadManager( 4823): DownloadService onCreate
D/EAS     ( 4597): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4597): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 4823): in removeSpuriousFiles
V/DownloadManager( 4823): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b09ff8 on behalf of 4823
I/LgeMiscReceiver( 4330): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4330): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4330): networkInfo.isConnected() = false
I/DownloadManager( 4823): in trimDatabase
D/MobileConnectivityChangeReceiver( 4862): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4862): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4823): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b0b9f0 on behalf of 4823
V/DownloadManager( 4823): DownloadService onStartCommand
,V/DownloadManager( 4823): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b0dba0 on behalf of 4823
,W/Settings( 4597): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMSGCM( 4931): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/ContextImpl( 4931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4948): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4948): CONNECT : WIFI_CONNECT
V/DownloadManager( 4823): DownloadService onDestroy
D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4005): onReceive
,D/AppUp4:CustFacade( 4005): Context : android.app.ReceiverRestrictedContext@42ad80f0
D/AppUp4:CustFacade( 4005): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4005): isOpenOperator : true
,D/AppUp4:CustFacade( 4005): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/SIMObserver( 2975): simInfo1
,I/AppUp4:EulaManager( 4005): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4005): begin check event
,I/AppUp4:CustModeStarterReceiver( 4005): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4823): DownloadService onCreate
,I/DownloadManager( 4823): in removeSpuriousFiles
,D/EAS     ( 4597): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4597): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4823): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b12228 on behalf of 4823
,V/DownloadManager( 4823): DownloadService onStartCommand
,I/DownloadManager( 4823): in trimDatabase
,V/DownloadManager( 4823): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4330): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4330): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b13b98 on behalf of 4823
I/LgeMiscReceiver( 4330): networkInfo.isConnected() = true
,D/PhoneState( 4330): setPdpRejectCasuse : false
,V/DownloadManager( 4823): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4862): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4597): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4862): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b15890 on behalf of 4823
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4823): DownloadService onDestroy
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4931): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/NFS     ( 4948): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4948): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1485): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1485): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/[LGHome]NumberBadge( 1485): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  966): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] connect :true
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/NetworkStateForAutoUpdateMonitor( 4005): [onReceive] request level :IDLE....
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/AppUp4:CustModeStarterReceiver( 4005): onReceive
D/AppUp4:CustFacade( 4005): Context : android.app.ReceiverRestrictedContext@42ad80f0
D/AppUp4:CustFacade( 4005): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4005): isOpenOperator : true
,D/AppUp4:CustFacade( 4005): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/SIMObserver( 2975): simInfo1
,I/AppUp4:EulaManager( 4005): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4005): begin check event
,I/AppUp4:CustModeStarterReceiver( 4005): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/DownloadManager( 4823): DownloadService onCreate
,D/EAS     ( 4597): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4597): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4823): in removeSpuriousFiles
,V/DownloadManager( 4823): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b19f58 on behalf of 4823
,I/DownloadManager( 4823): in trimDatabase
V/DownloadManager( 4823): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4823): DownloadService onStartCommand
V/DownloadManager( 4823): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b1b8c8 on behalf of 4823
,V/DownloadManager( 4823): created cursor android.database.sqlite.SQLiteCursor@42b1d158 on behalf of 4823
,I/LgeMiscReceiver( 4330): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4330): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4330): networkInfo.isConnected() = true
,D/PhoneState( 4330): setPdpRejectCasuse : false
,W/Settings( 4597): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4862): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4862): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4823): DownloadService onDestroy
,D/LGDMClient( 2857): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2857): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4931): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2857): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 4931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4948): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4948): CONNECT : WIFI_CONNECT
E/LGDMClient( 2857): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2857): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2857): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2857): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/WifiServiceExtension(  966): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  966): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4961): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  966): Killing 4744:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  966): Killing 4614:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2012): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.462936 Y: -0.411743 Z: 9.746094 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.462936 .y:-0.411743 .z:9.746094
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/Finsky  ( 4228): [396] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4228): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  966): Killing 4782:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.453400 Y: -0.409027 Z: 9.753616 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453400 .y:-0.409027 .z:9.753616
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2012): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3706): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3706): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  966): Handling package changes for user 0
,I/ActivityManager(  966): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5164 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5164): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "sms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  966):   Scheme: "smsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mms"
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mmsto"
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): battery changed pluggedType: 2
,I/Babel   ( 5164): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5164): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5164): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5164): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5164): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5164): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5164): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5164): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5164): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5164): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5164): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5164): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5164): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5164): MmsConfig.loadFromResources
,E/Babel   ( 5164): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5164): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5164): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/LGRssiData( 5164): [loadRssi] File not exist 
V/LGRssiData( 5164): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5164): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5164): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5164): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5164): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4005): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4005): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4005): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/GmsNetworkLocationProvi( 1423): DISABLE
,I/AppUp4:CustModeStarterReceiver( 4005): onReceive
D/AppUp4:CustFacade( 4005): Context : android.app.ReceiverRestrictedContext@42ad80f0
,D/AppUp4:CustFacade( 4005): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4005): isOpenOperator : true
,D/AppUp4:CustFacade( 4005): isPhone : true
,I/LicenseContentProvider( 2975): start selecting data
,D/SIMObserver( 2975): simInfo1
I/AppUp4:EulaManager( 4005): getAgreementForKK : Eula agreement is false
I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/AppUp4:CustModeStarterReceiver( 4005): begin check event
D/AppUp4:Utils( 4005): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4005): Event For Nothing, skip.
,I/ActivityManager(  966): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5210 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 22ms
,D/HyLog   ( 5210): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5210): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5210): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,I/SystemConfig( 5210): BUILD Country: EU
,I/SystemConfig( 5210): BUILD Operator: OPEN
,D/LocationProviderProxy(  966): applying state to connected service
,D/LocationProviderProxy(  966): applying state to connected service
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
I/ActivityManager(  966): Killing 4693:com.test.thalitest/u0a304 (adj 15): empty #17
,I/SystemConfig( 5210): systemFeature RCS result false
,D/SystemConfig( 5210): refreshRcsSupport() :false
I/ActivityManager(  966): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5227 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,D/WifiService(  966): Client connection lost with reason: 4
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/WindowState(  966): WIN DEATH: Window{440054a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/HyLog   ( 5227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5227): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5227): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43f77b28 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1485): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  966): Killing 4823:android.process.media/u0a23 (adj 15): empty #17
,W/Binder  ( 1316): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1316): java.lang.NullPointerException
W/Binder  ( 1316): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1316): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1316): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1316): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  966): IME STATUS OFF
W/InputMethodManagerService(  966): Got RemoteException sending setActive(false) notification to pid 4693 uid 10304
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Killing 4597:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2671): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e96c80 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1960): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1960): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  966): Delaying start of: ServiceRecord{44b9e628 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1960): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1960): GC_CONCURRENT freed 1902K, 22% free 19549K/24832K, paused 3ms+5ms, total 47ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2671): UpdateCorporaTask done [took 264 ms] updated apps [took 264 ms] 
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2012): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  966): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  966): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  966): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  966): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  966): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  966): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  966): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  966): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
,D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2012): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/GAV4    ( 5164): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/PowerManagerService(  966): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  966): [updateScreenState] screen on = false
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  966): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8472 usec
D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  966): hal_acquire_resources
,I/qcom_sensors_hal(  966): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  966): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  966): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  966): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  966): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  966): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  966): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.450516 Y: -0.405502 Z: 9.774292 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450516 .y:-0.405502 .z:9.774292
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2012): nl80211: survey data missing!
,D/WifiStateMachine(  966): handleMessage: X
,I/Sensors (  392): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.455917 Y: -0.412155 Z: 9.783081 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455917 .y:-0.412155 .z:9.783081
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  966): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  966): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  966): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  966): proximitySensorChanged  positive = true
I/KnockOnPowerController(  966): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.460190 Y: -0.403595 Z: 9.794922 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460190 .y:-0.403595 .z:9.794922
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.467957 Y: -0.397186 Z: 9.787994 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467957 .y:-0.397186 .z:9.787994
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.455902 Y: -0.396698 Z: 9.771027 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455902 .y:-0.396698 .z:9.771027
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.435776 Y: -0.405228 Z: 9.764359 
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.453522 Y: -0.409668 Z: 9.757706 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.435776 .y:-0.405228 .z:9.764359
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  966): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@45020220)
,D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/KeyguardViewMediator( 1140): handleNotifyScreenOn
,D/KeyguardViewManager( 1140): onScreenTurnedOn()
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7dab450
,V/KeyguardServiceDelegate(  966): **** SHOWN CALLED ****
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
I/WindowManager(  966): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.438019 Y: -0.385269 Z: 9.797638 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438019 .y:-0.385269 .z:9.797638
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  966): handleScreenStateChanged: true
,D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  966): doString: SIGNAL_POLL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2012): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  966): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  966): stopMonitoring
,D/wpa_supplicant( 2012): nl80211: survey data missing!
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131127
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=132097
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  966): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2012): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2012): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  966): handleMessage: X
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 966
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{435c25b0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/WeatherAncestor( 1824): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 0:2:23
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3706): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3706): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
,D/WeatherAncestor( 1824): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 0:2:23
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1824): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2,
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2,
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237,
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  966): Excessive delay in blankDisplay() while turning screen off: 409ms
D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450738943898, nextTick: 36133, mDrawingTime: 1
D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450738943992, nextTick: 36040, mDrawingTime: 0
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=4
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
,D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:2:24
,D/WeatherService( 1824): 2 : ACTION screen on
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 0:2:24
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.459686 Y: -0.394989 Z: 9.776459 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459686 .y:-0.394989 .z:9.776459
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
,V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1}
D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
I/[LGHome]EVENT( 1485): [Launcher.java:894:onPause()]onPause
D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
D/qcom_sensors_hal(  966): hal_acquire_resources
D/qcom_sensors_hal(  966): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  966): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,I/LGImmersionVibrator(  966): Vibrator off
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/qcom_sensors_hal(  966): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  966): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  966): hal_smgr_report_delete: Rcvd success response from request
I/[LGHome]EVENT( 1485): [Launcher.java:4955:onStop()]onStop
D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  966): handleScreenStateChanged: false
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
D/WifiStateMachine(  966): processMsg: ConnectModeState
D/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiStateMachine(  966): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  966): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2012): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2012): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 966
V/SRS_Proc(  270): ParamSet string: screen_state=off
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
,D/KeyguardViewManager( 1140): onScreenTurnedOff()
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{42e07db0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  966): CMD_SCREEN_OFF 
D/WifiController(  966): shouldWifiStayAwake TRUE
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1157): clear
D/wpa_supplicant( 2012): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  966):    returned true
D/WifiStateMachine(  966): handleMessage: X
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
D/NativeNfcBrcmPowerMode( 1471): setPowerMode; state=2
,I/[LGHome]EVENT( 1485): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/WeatherService( 1824): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:2:24
,D/WeatherService( 1824): 2 : ACTION screen off
,D/WeatherService( 1824): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 0:2:24
D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
,V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
E/Parcel  (  404): Reading a NULL string not supported here.
,E/Parcel  (  404): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1471): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/NfcService( 1471): NFC-C OFF
D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  966): ACTION_SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  392): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131155
,D/WifiStateMachine(  966): processMsg: ConnectedState
D/WifiStateMachine(  966): processMsg: L2ConnectedState
,D/WifiStateMachine(  966): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1559): Vacuum at: now=1450738952526 tag=VacuumService
,I/GoogleURLConnFactory( 1559): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1559): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1559): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1559): GC_CONCURRENT freed 1798K, 28% free 18027K/24832K, paused 3ms+5ms, total 67ms
,W/Uploader( 1559):  no longer exists, so no auth token.
,W/Uploader( 1559): No account for auth token provided
,D/dalvikvm(  966): GC_EXPLICIT freed 2851K, 47% free 30651K/56880K, paused 11ms+14ms, total 198ms
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450738961812598119; DSPS: 5273945; Offset: 1450738800864569555
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450738980035, nextTick: 59998, mDrawingTime: 0
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450738980036, nextTick: 59997, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450738981813966370; DSPS: 5929350; Offset: 1450738800864564515
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739001815305535; DSPS: 6584754; Offset: 1450738800864560907
,D/wpa_supplicant( 2012): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:96]
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739021815761120; DSPS: 7240128; Offset: 1450738800864589245
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739040047, nextTick: 59985, mDrawingTime: 0
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739040049, nextTick: 59978, mDrawingTime: 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739041817123413; DSPS: 7895534; Offset: 1450738800864547730
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739061818450645; DSPS: 8550937; Offset: 1450738800864562706
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739081819790573; DSPS: 9206341; Offset: 1450738800864559861
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739100037, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739100042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739101821162674; DSPS: 9861746; Offset: 1450738800864558671
,D/wpa_supplicant( 2012): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: BSS: Remove id 5 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: BSS: Remove id 6 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2012): wlan0: BSS: Remove id 7 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2012): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 a0:c5:62:7a:49:97]
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81],
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 64:7c:34:38:27:cc]
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739121822520229; DSPS: 10517150; Offset: 1450738800864573452
,D/dalvikvm( 2658): GC_CONCURRENT freed 7763K, 32% free 16890K/24832K, paused 3ms+2ms, total 46ms
,D/dalvikvm( 2658): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x43562528: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1559): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1559): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1559): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1559): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1559): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1559): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1559): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1559): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4228): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4228): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4228): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4228): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4228): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4228): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4228): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4228): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4228): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4228): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739141823921104; DSPS: 11172556; Offset: 1450738800864570519
,I/LocationManagerService(  966): remove 43777688
,D/LocationManagerService(  966): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  966): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  966): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2658): GC_CONCURRENT freed 1879K, 32% free 17058K/24832K, paused 6ms+2ms, total 32ms
,D/dalvikvm( 2658): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2658): GC_CONCURRENT freed 1715K, 31% free 17269K/24832K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 2658): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Mlt MonitorService( 2658): parseLastkmsg to dump
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739160045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739160055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739161825344630; DSPS: 11827963; Offset: 1450738800864559718
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739181826694744; DSPS: 12483367; Offset: 1450738800864567059
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739201828030297; DSPS: 13138771; Offset: 1450738800864559839
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739220048, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739220051, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739221828964490; DSPS: 13794161; Offset: 1450738800864578504
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739241830258637; DSPS: 14449564; Offset: 1450738800864560395
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739261830691814; DSPS: 15104938; Offset: 1450738800864566326
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739280046, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739280055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739281831645343; DSPS: 15760329; Offset: 1450738800864573810
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739301833540535; DSPS: 16415751; Offset: 1450738800864576912
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739321833979683; DSPS: 17071126; Offset: 1450738800864558297
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739340027, nextTick: 60002, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739340046, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739341835385680; DSPS: 17726532; Offset: 1450738800864560485
,W/ProcessCpuTracker(  966): Skipping unknown process pid 5732
,W/ProcessCpuTracker(  966): Skipping unknown process pid 5733
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  966): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  966): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739361836289702; DSPS: 18381921; Offset: 1450738800864579497
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739381837174895; DSPS: 19037311; Offset: 1450738800864549163
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739400040, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739400043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739401838150574; DSPS: 19692702; Offset: 1450738800864578797
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739421839531114; DSPS: 20348108; Offset: 1450738800864555529
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739441840897765; DSPS: 21003512; Offset: 1450738800864579406
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739460031, nextTick: 59984, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739460045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739461842474444; DSPS: 21658924; Offset: 1450738800864569171
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739481843132908; DSPS: 22314306; Offset: 1450738800864556248
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739501843599323; DSPS: 22969681; Offset: 1450738800864564900
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739520032, nextTick: 59992, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739520056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739521844998925; DSPS: 23625087; Offset: 1450738800864560693
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739541846358780; DSPS: 24280491; Offset: 1450738800864577775
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739561846830199; DSPS: 24935867; Offset: 1450738800864560912
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739580047, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739580055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739581847727875; DSPS: 25591256; Offset: 1450738800864573579
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739601848161685; DSPS: 26246630; Offset: 1450738800864580143
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739621848615610; DSPS: 26902005; Offset: 1450738800864576304
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739640040, nextTick: 59977, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739640050, nextTick: 59982, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739641849079409; DSPS: 27557380; Offset: 1450738800864582339
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  966): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  966): Done.
,D/QcConnectivityService(  966): Setting timer for 720seconds
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739661849991408; DSPS: 28212771; Offset: 1450738800864548293
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739681850883882; DSPS: 28868160; Offset: 1450738800864555757
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739700039, nextTick: 59968, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739700054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739701851353561; DSPS: 29523535; Offset: 1450738800864567673
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739721852957456; DSPS: 30178947; Offset: 1450738800864584654
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739741853400336; DSPS: 30834322; Offset: 1450738800864569770
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739760032, nextTick: 59979, mDrawingTime: 11
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739760057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739761853867744; DSPS: 31489697; Offset: 1450738800864579414
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739781854810304; DSPS: 32145088; Offset: 1450738800864575929
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739801855718681; DSPS: 32800478; Offset: 1450738800864568779
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739820032, nextTick: 59990, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739820057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739821856145744; DSPS: 33455852; Offset: 1450738800864568596
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739841857064686; DSPS: 34111242; Offset: 1450738800864572011
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739861857508248; DSPS: 34766616; Offset: 1450738800864588327
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739880043, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739880055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739881858408264; DSPS: 35422006; Offset: 1450738800864572815
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739901859287519; DSPS: 36077395; Offset: 1450738800864567061
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739921859756648; DSPS: 36732770; Offset: 1450738800864578426
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739940030, nextTick: 59993, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450739940057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739941861138320; DSPS: 37388175; Offset: 1450738800864586807
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739961862028376; DSPS: 38043565; Offset: 1450738800864561335
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450739981862921783; DSPS: 38698954; Offset: 1450738800864569733
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740000045, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740000055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740001863373032; DSPS: 39354329; Offset: 1450738800864563218
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740021864277477; DSPS: 40009719; Offset: 1450738800864552136
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740041864714171; DSPS: 40665093; Offset: 1450738800864561584
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740060034, nextTick: 59983, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740060042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740061865625483; DSPS: 41320483; Offset: 1450738800864557368
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740081866060200; DSPS: 41975857; Offset: 1450738800864564839
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740101866504473; DSPS: 42631231; Offset: 1450738800864581866
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740120033, nextTick: 59978, mDrawingTime: 10
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740120045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740121867458385; DSPS: 43286623; Offset: 1450738800864559216
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740141867915037; DSPS: 43941998; Offset: 1450738800864558104
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740161868373238; DSPS: 44597373; Offset: 1450738800864558541
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740180046, nextTick: 59979, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740180057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740181868827996; DSPS: 45252748; Offset: 1450738800864555536
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740201869762341; DSPS: 45908138; Offset: 1450738800864574353
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740221870213764; DSPS: 46563513; Offset: 1450738800864568013
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740240038, nextTick: 59974, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740240051, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740241871120944; DSPS: 47218903; Offset: 1450738800864559665
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740261874004231; DSPS: 47874357; Offset: 1450738800864574300
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740281874439998; DSPS: 48529732; Offset: 1450738800864552303
,D/dalvikvm( 3873): GC_FOR_ALLOC freed 365K, 2% free 37805K/38444K, paused 31ms, total 34ms
,D/GCM     ( 1559): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  966): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740300047, nextTick: 59973, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740300054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740301875327529; DSPS: 49185121; Offset: 1450738800864554824
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740321876703794; DSPS: 49840526; Offset: 1450738800864557798
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740341877175026; DSPS: 50495901; Offset: 1450738800864571267
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740360046, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740360049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740361877644753; DSPS: 51151276; Offset: 1450738800864583230
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  966): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  966): Done.
,D/QcConnectivityService(  966): Setting timer for 720seconds
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740381878536567; DSPS: 51806666; Offset: 1450738800864559517
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740401879003686; DSPS: 52462041; Offset: 1450738800864568872
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740420050, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740420054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740421879464535; DSPS: 53117416; Offset: 1450738800864571957
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740441880790064; DSPS: 53772820; Offset: 1450738800864554713
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740461881221300; DSPS: 54428194; Offset: 1450738800864558703
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740480044, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740480054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740481881689748; DSPS: 55083569; Offset: 1450738800864569387
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740501886617899; DSPS: 55739091; Offset: 1450738800864553691
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740521887477887; DSPS: 56394479; Offset: 1450738800864559186
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740540044, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740540054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740541887944660; DSPS: 57049854; Offset: 1450738800864568196
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740561888832030; DSPS: 57705243; Offset: 1450738800864570556
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740581899914935; DSPS: 58360966; Offset: 1450738800864575580
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740600045, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740600056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740601900342432; DSPS: 59016340; Offset: 1450738800864575831
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740621901302952; DSPS: 59671732; Offset: 1450738800864559788
,I/ProcessStatsService(  966): Prepared write state in 18ms
,D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  966): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-31-55.bin
,I/EventLogService( 1960): Aggregate from 1450738925330 (log), 1450738829600 (data)
,I/GLSUser ( 1559): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1559): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1559): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1559): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1559): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740641901752832; DSPS: 60327106; Offset: 1450738800864582422
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740660034, nextTick: 59983, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740660042, nextTick: 59990, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740661904749481; DSPS: 60982565; Offset: 1450738800864557831
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740681905212633; DSPS: 61637940; Offset: 1450738800864563219
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740701905661333; DSPS: 62293315; Offset: 1450738800864554156
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740720031, nextTick: 59986, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1450740720056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1450740721906637362; DSPS: 62948706; Offset: 1450738800864584140
,TIME-OUT KILL (timeout was 1800000ms)
```
