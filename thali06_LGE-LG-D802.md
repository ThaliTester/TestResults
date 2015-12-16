#### Test 50650278e989a4f_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1972): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1972): launchTask
W/dalvikvm( 1972): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1972): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1972): Module APK com.google.android.play.games already loaded
,V/ConfigFetchTask( 1972): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1V4i8nWq5Ikr1mHtLU2b4MmGct_ITHakY5RRopTWXsrfn6pKKn-0L6V0Acz9ZHTPUwb3h_cbb-NOlfw3iKQFxpKHM-z4mJbtiNMmv9S7qMm0A8fakZNA82XRz2Ni8K95c8LM5sra12oxOUnF_6KhWcSh2zuGCR7JBP8eeq_M55oAQlTf_GuTA7g-xkW-pP9qkbol-79zBiGOAE0LV9ctyVkdUBK_iC-YPOgmHB5zrm5PI5ehI4
D/ChimeraCfgMgr( 1972): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1972): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1972): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1972): No vision deps
I/GoogleURLConnFactory( 1972): Using platform SSLCertificateSocketFactory
W/GAV2    ( 4555): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  967): Killing 4025:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2}
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
W/BaseAppContext( 1972): Using Auth Proxy for data requests.
W/BaseAppContext( 1972): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1972): CP2 sync disabled
I/dalvikvm( 1972): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1972): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1972): VFY: replacing opcode 0x6e at 0x000e
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/BaseAppContext( 1972): Using Auth Proxy for data requests.
W/BaseAppContext( 1972): Using Auth Proxy for data requests.
W/BaseAppContext( 1972): Using Auth Proxy for data requests.
W/BaseAppContext( 1972): Using Auth Proxy for data requests.
D/dalvikvm( 1972): GC_CONCURRENT freed 1522K, 22% free 19417K/24832K, paused 3ms+2ms, total 30ms
I/ConfigFetchService( 1972): fetch service done; releasing wakelock
I/ConfigFetchService( 1972): stopping self
D/AndroidRuntime( 4604): 
D/AndroidRuntime( 4604): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4604): CheckJNI is OFF
D/dalvikvm( 4604): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4604): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4604): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4604): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4604): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4604): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1972): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/ChimeraCfgMgr( 1972): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1972): Module APK com.google.android.play.games already loaded
D/Icing   ( 1972): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1972): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/memtrack( 4604): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4604): failed to load memtrack module: -2
D/AndroidRuntime( 4604): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4604
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (118 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  967): startService SlideAside
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{43335ff8 stackId=1, 2 tasks}
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/AndroidRuntime( 4604): Shutting down VM
D/UsbSettingsControl( 2613): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2613): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4604): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 1ms
I/SlideAside( 3709): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3709): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3709): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4636 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4636): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4636): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4636): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/BubblePopupHelper( 1146): isShowingBubblePopup : false
V/WebViewChromium( 4636): Binding Chromium to the background looper Looper (main, tid 1) {4289aa70}
I/chromium( 4636): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4636): Initializing chromium process, renderers=0
W/chromium( 4636): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4636): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4636): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4636): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4636): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4636): Remote Branch: 
I/Adreno-EGL( 4636): Local Patches: 
I/Adreno-EGL( 4636): Reconstruct Branch: 
I/dalvikvm( 4636): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4636): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4636): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4636): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4636): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4636): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4636): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4636): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4636): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4636): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4636): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4636): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4636): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4636): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4636): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4636): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4636): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
W/BaseRuntimeLoader( 4636): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4636): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4636): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4636): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/OpenGLRenderer( 4636): Enabling debug mode 0
W/AwContents( 4636): nativeOnDraw failed; clearing to background color.
W/AwContents( 4636): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  967): IME STATUS OFF
I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +464ms
I/ActivityManager( 4636): Timeline: Activity_idle id: android.os.BinderProxy@4289c150 time:110801
D/JsMessageQueue( 4636): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4636): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a1850
D/dalvikvm( 4636): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428a1850
D/jxcore_app_log( 4636): JniHelper::setJavaVM(0x41767838), pthread_self() = 1632407504
D/JX-Cordova( 4636): jxcore cordova android initializing
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3} time:111087
D/ActivityManager(  967): no-history finish of ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{42dedf70 ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2 f}
D/UsbSettings( 2613): [AUTORUN] onStop()
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4636): GC_CONCURRENT freed 2780K, 12% free 21872K/24832K, paused 3ms+1ms, total 40ms
,D/dalvikvm( 4636): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 199K, 13% free 21847K/24832K, paused 34ms, total 34ms
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2030): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
D/dalvikvm( 4636): GC_FOR_ALLOC freed 185K, 12% free 21878K/24832K, paused 25ms, total 25ms
I/dalvikvm-heap( 4636): Grow heap (frag case) to 23.677MB for 144892-byte allocation
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 255K, 13% free 21925K/24976K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4636): Grow heap (frag case) to 23.792MB for 217334-byte allocation
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 367K, 13% free 21999K/25192K, paused 21ms, total 22ms
,I/dalvikvm-heap( 4636): Grow heap (frag case) to 23.968MB for 325996-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
D/dalvikvm( 4636): GC_FOR_ALLOC freed 568K, 14% free 22121K/25512K, paused 23ms, total 23ms
I/dalvikvm-heap( 4636): Grow heap (frag case) to 24.243MB for 488990-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false,
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 865K, 15% free 22298K/25992K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4636): Grow heap (frag case) to 24.648MB for 733480-byte allocation
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 1285K, 16% free 22555K/26712K, paused 23ms, total 24ms
,D/dalvikvm( 4636): GC_CONCURRENT freed 1675K, 15% free 22928K/26712K, paused 2ms+3ms, total 44ms
,D/dalvikvm( 4636): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 370K, 15% free 22884K/26712K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4636): Grow heap (frag case) to 26.095MB for 1650320-byte allocation
,D/dalvikvm( 4636): GC_CONCURRENT freed 1716K, 17% free 23692K/28324K, paused 2ms+2ms, total 49ms
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 1335K, 17% free 23535K/28324K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4636): Grow heap (frag case) to 27.517MB for 2475476-byte allocation
,D/dalvikvm( 4636): GC_CONCURRENT freed 2073K, 21% free 24324K/30744K, paused 2ms+2ms, total 56ms
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.463303 Y: -0.412064 Z: 9.743668 
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.424454 Y: -0.390976 Z: 9.770279 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.463303 .y:-0.412064 .z:9.743668
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.475754 Y: -0.425278 Z: 9.757812 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.475754 .y:-0.425278 .z:9.757812
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/dalvikvm( 4636): GC_CONCURRENT freed 2460K, 21% free 24484K/30744K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4636): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 154K, 21% free 24430K/30744K, paused 38ms, total 38ms
,I/dalvikvm-heap( 4636): Grow heap (frag case) to 29.572MB for 3713210-byte allocation
,D/dalvikvm( 4636): GC_CONCURRENT freed 2949K, 27% free 25431K/34372K, paused 4ms+2ms, total 56ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,D/dalvikvm( 4636): GC_FOR_ALLOC freed 470K, 26% free 25450K/34372K, paused 23ms, total 23ms
,W/jxcore-log( 4636): Initializing JXcore engine
,W/jxcore-log( 4636): JXcore engine is ready
,D/dalvikvm( 4636): GC_CONCURRENT freed 345K, 19% free 28073K/34372K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 4636): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4636): Starting JXcore engine
,W/jxcore-log( 4636): Platform android
W/jxcore-log( 4636): 
,W/jxcore-log( 4636): Process ARCH arm
W/jxcore-log( 4636): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
I/jxcore-log( 4636): JXcore Cordova bridge is ready!
I/jxcore-log( 4636): 
W/jxcore-log( 4636): JXcore engine is started
I/chromium( 4636): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4636): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/chromium( 4636): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4555): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/jxcore-log( 4636): Toggling radios to true
I/jxcore-log( 4636): 
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44ec50a0:true
,D/BluetoothAdapter( 4636): enable(): BT is already enabled..!
D/WifiService(  967): New client listening to asynchronous messages
D/WifiStateMachine(  967): handleMessage: E msg.what=131145
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doBoolean: DISCONNECT
,I/jxcore-log( 4636): Radios toggled
I/jxcore-log( 4636): 
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2030): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2030): wlan0: Cancelling scan request
D/wpa_supplicant( 2030): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2030): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2030): TDLS: Tear down peers
D/wpa_supplicant( 2030): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4636): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4636): 
,I/jxcore-log( 4636): Perf Test app loaded loaded
I/jxcore-log( 4636): 
D/WifiService(  967): setWifiEnabled: true pid=4636, uid=10304
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  967): disconnect pid=4636, uid=10304
,D/WifiService(  967): reconnect pid=4636, uid=10304
I/Choreographer( 4636): Skipped 68 frames!  The application may be doing too much work on its main thread.
,D/wpa_supplicant( 2030): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2030): wlan0: Deauthentication notification
D/wpa_supplicant( 2030): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2030): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2030): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2030): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2030): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2030): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8894d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2030):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2030): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2030): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2030): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2030): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2030): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2030): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2030): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2030): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2030): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2030): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2030): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2030): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2030): nl80211: Event message available
D/wpa_supplicant( 2030): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2030): nl80211: Ignore disconnect event triggered during reassociation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
W/Settings(  967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  967): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131146
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiNative-wlan0(  967): doBoolean: RECONNECT
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2030): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2030): Fast associate: Old scan results
D/wpa_supplicant( 2030): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2030): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2030): wlan0: nl80211: scan request
D/wpa_supplicant( 2030): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2030): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2030): nl80211: Event message available
D/wpa_supplicant( 2030): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2030): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  967):    returned true
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/WifiStateMachine(  967): processMsg: DisconnectingState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection lost
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2030): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2030): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2030): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2030): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2030): wpa_driver_nl80211_driver_cmd OK len = 0, 2
I/jxcore-log( 4636): check test folder
I/jxcore-log( 4636): 
D/WifiNative-wlan0(  967):    returned true
D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4636): found test : ./testFindPeers.js
I/jxcore-log( 4636): 
D/WifiP2pService(  967): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  967): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  967): transitionTo: destState=DisconnectedState
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
D/QCNEA   (  399): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  399): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  399): |CAC| updateNetCfgInfo
V/QCNEA   (  399): |CAC| *********************************************
V/QCNEA   (  399): |CAC|                   Netconfig               
V/QCNEA   (  399): |CAC| *********************************************
V/QCNEA   (  399): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  399): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  399): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  399): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  399): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  399): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  399): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  399): |CAC| *********************************************
D/QCNEA   (  399): |CAC| Received bssid= 
D/QCNEA   (  399): |CAC| net type = 3
V/QCNEA   (  399): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  399): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  399): |CAC| 	ssid           =NG700
V/QCNEA   (  399): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  399): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  399): |CAC| *********************************************
D/QCNEA   (  399): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  399): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  399): |CAC| dispatchNetCfg: updating:0xb85808dc
D/QCNEA   (  399): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiHS20(  967): hidePasspointNotification off =false
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/KeyguardUpdateMonitor( 1146): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1162): handleWifiStateChangedEvent: 0
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  967): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  967): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
,D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
,I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4687 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
I/jxcore-log( 4636): found test : ./testSendData.js
I/jxcore-log( 4636): 
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1146): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
D/HyLog   ( 4687): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4687): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4687): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
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
,D/NetUtils(  967): android_net_utils_resetConnections in env=0x619b8ae0 clazz=0x6d600001 iface=wlan0 mask=0x3
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
,I/PCSuite ( 4687): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/NativeCrypto( 1545): Read error: ssl=0x62393428: I/O error during system call, Connection timed out
D/PCSuite ( 4687): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4687): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1545): SSL shutdown failed: ssl=0x62393428: I/O error during system call, Broken pipe
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4722 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  967): Killing 4129:com.google.android.talk/u0a77 (adj 15): empty #17
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/HyLog   ( 4722): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4722): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4722): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/chromium( 4636): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4722): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4722): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4722): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4722): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4722): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4722): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4722): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4722): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4722): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  967): Killing 3111:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  967): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1545): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1162): usb Uevent not necessary.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 3987): onReceive
,D/AppUp4:CustFacade( 3987): Context : android.app.ReceiverRestrictedContext@428ba650
,D/AppUp4:CustFacade( 3987): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3987): isOpenOperator : true
,D/AppUp4:CustFacade( 3987): isPhone : true
,I/LicenseContentProvider( 2966): start selecting data
,D/SIMObserver( 2966): simInfo1
,I/AppUp4:EulaManager( 3987): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3987): begin check event
,I/AppUp4:CustModeStarterReceiver( 3987): Event For GoodConnectivity
,D/wpa_supplicant( 2030): nl80211: Event message available
D/wpa_supplicant( 2030): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2030): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2030): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2030): nl80211: Received scan results (11 BSSes)
D/wpa_supplicant( 2030): nl80211: Survey data missing
D/wpa_supplicant( 2030): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2030): wlan0: BSS: Add new id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Add new id 8 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600'
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Add new id 9 BSSID fc:6f:b7:3e:78:0a SSID 'UPC249917252'
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Add new id 10 BSSID 64:7c:34:95:11:85 SSID 'Chopin_143'
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): BSS: last_scan_res_used=11/32 last_scan_full=0
D/wpa_supplicant( 2030): wlan0: New scan results available
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2030): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2030): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2030): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2030): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2030): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2030): WPS: AP fc:6f:b7:3e:78:0a type 0 added
D/wpa_supplicant( 2030): WPS: AP 64:7c:34:95:11:85 type 0 added
D/wpa_supplicant( 2030): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2030): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2030): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2030): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2030): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2030): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 2030): WPS: AP[6] fc:6f:b7:3e:78:0a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2030): WPS: AP[7] 64:7c:34:95:11:85 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2030): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2030): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-46 wps
D/wpa_supplicant( 2030): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2030): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2030): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2030): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
,D/wpa_supplicant( 2030): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2030): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2030): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2030): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2030): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2030): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2030): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb88965a8  current_ssid=0x0,
D/wpa_supplicant( 2030): scard is not null..
D/wpa_supplicant( 2030): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2030): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2030): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2030): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2030): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2030): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2030): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2030): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2030): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2030): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2030): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2030): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2030): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 2030): wlan0: Cancelling scan request,
,D/wpa_supplicant( 2030): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2030): wlan0: WPA: clearing own WPA/RSN IE,
D/wpa_supplicant( 2030): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2030): RSN: PMKSA cache search - network_ctx=0xb88965a8 try_opportunistic=0,
D/wpa_supplicant( 2030): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2030): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2030): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2030): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2030): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2030): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2030): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2030): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2030): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2030): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2030): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2030): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2030): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2030): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 2030): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2030): nl80211: Unsubscribe mgmt frames handle 0xb8895590 (mode change),
D/wpa_supplicant( 2030): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=2): 04 0b
,D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590,
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590,
,D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 2030): nl80211: Register frame type=0xd0 nl_handle=0xb8895590
D/wpa_supplicant( 2030): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2030): nl80211: Connect (ifindex=23)
,D/wpa_supplicant( 2030):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030):   * freq=2412
D/wpa_supplicant( 2030):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2030):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2030):   * Auth Type 0
D/wpa_supplicant( 2030):   * WPA Versions 0x2
D/wpa_supplicant( 2030): nl80211: Connect request send successfully,
D/wpa_supplicant( 2030): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2030): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2030): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2030): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2030): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2030): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 a0:c5:62:7a:49:96],
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 fc:6f:b7:3e:78:0a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 64:7c:34:95:11:85],
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
D/WifiStateMachine(  967): handleMessage: E msg.what=147461
,D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  967): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2030): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
I/ActivityManager(  967): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4753 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/WifiMonitor(  967): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
,D/HyLog   ( 4753): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4753): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4753): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2030): nl80211: Event message available
,D/wpa_supplicant( 2030): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2030): nl80211: Connect event
D/wpa_supplicant( 2030): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2030): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2030): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2030): wlan0: Association info event
D/wpa_supplicant( 2030): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2030): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2030): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2030): wlan0: freq=2412 MHz
D/wpa_supplicant( 2030): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2030): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2030): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2030): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2030): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2030): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2030): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): scard is not null..
D/wpa_supplicant( 2030): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2030): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2030): TDLS: Remove peers on association
D/wpa_supplicant( 2030): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2030): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2030): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2030): EAPOL: enable timer tick
D/wpa_supplicant( 2030): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2030): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2030): wlan0: Cancelling scan request
D/wpa_supplicant( 2030): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2030): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2030): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2030): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2030): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  967): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  967): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2030): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 73 cc 89 a1 9e b4 65 01 ea 41 9a 41 a9 e1 a4 ...
D/wpa_supplicant( 2030): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2030): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2030): wlan0:   EAPOL-Key type=2
,D/wpa_supplicant( 2030): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2030): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2030):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2030):   key_nonce - hexdump(len=32): 73 cc 89 a1 9e b4 65 01 ea 41 9a 41 a9 e1 a4 a6 82 f2 44 7e 7c d7 a8 fb c8 73 41 66 9f e7 d1 c6
D/wpa_supplicant( 2030):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 73 cc 89 a1 9e b4 65 01 ea 41 9a 41 a9 e1 a4 ...
D/wpa_supplicant( 2030): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2030): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2030): Get randomness: len=32 entropy=11
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
,D/WifiStateMachine(  967): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/wpa_supplicant( 2030): WPA: Renewed SNonce - hexdump(len=32): 3e 00 27 90 57 c8 e3 89 c4 cf da 6c 41 5b f9 eb 9e 71 0b eb e9 eb 37 e6 8e cc 64 0b ec ba 77 dc
D/wpa_supplicant( 2030): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): WPA: Nonce1 - hexdump(len=32): 3e 00 27 90 57 c8 e3 89 c4 cf da 6c 41 5b f9 eb 9e 71 0b eb e9 eb 37 e6 8e cc 64 0b ec ba 77 dc
D/wpa_supplicant( 2030): WPA: Nonce2 - hexdump(len=32): 73 cc 89 a1 9e b4 65 01 ea 41 9a 41 a9 e1 a4 a6 82 f2 44 7e 7c d7 a8 fb c8 73 41 66 9f e7 d1 c6
D/wpa_supplicant( 2030): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2030): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2030): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2030): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2030): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2030): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2030): WPA: Derived Key MIC - hexdump(len=16): 93 95 d2 c0 2a 50 77 39 65 04 f8 2c 10 f9 f0 a9
D/wpa_supplicant( 2030): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 3e 00 27 90 57 c8 e3 89 c4 cf da 6c 41 5b f9 ...
,D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2030): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2030): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 73 cc 89 a1 9e b4 65 01 ea 41 9a 41 a9 e1 a4 ...
D/wpa_supplicant( 2030): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2030): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2030): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2030): wlan0:   key_length=16 key_data_length=56
,D/wpa_supplicant( 2030):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2030):   key_nonce - hexdump(len=32): 73 cc 89 a1 9e b4 65 01 ea 41 9a 41 a9 e1 a4 a6 82 f2 44 7e 7c d7 a8 fb c8 73 41 66 9f e7 d1 c6
D/wpa_supplicant( 2030):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030):   key_rsc - hexdump(len=8): 9c 81 00 00 00 00 00 00
D/wpa_supplicant( 2030):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2030):   key_mic - hexdump(len=16): 8e 8e 71 62 e8 77 77 d3 3a 21 71 05 fc 77 f1 24
D/wpa_supplicant( 2030): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 73 cc 89 a1 9e b4 65 01 ea 41 9a 41 a9 e1 a4 ...
D/wpa_supplicant( 2030): RSN: encrypted key data - hexdump(len=56): a6 0d e3 f1 71 09 06 76 68 09 19 0f e7 ef 51 b7 e3 91 0d 1d b7 a5 4f b6 09 b8 24 00 1d 8d e8 22 ...
D/wpa_supplicant( 2030): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2030): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2030): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2030): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 e6 70 ...
D/wpa_supplicant( 2030): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2030): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2030): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2030): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2030): WPA: Derived Key MIC - hexdump(len=16): 9f 4e 3d 4a 3f 4d f1 85 16 8b 2d a1 0b b6 40 3a
D/wpa_supplicant( 2030): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2030): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8895c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2030):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2030): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2030): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2030): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2030): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2030): WPA: RSC - hexdump(len=6): 9c 81 00 00 00 00
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f6003a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2030):    broadcast key
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2030): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2030): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2030): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 2030): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2030): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2030): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2030): EAPOL: External notification - EAP success=1
D/WifiMonitor(  967): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: DisconnectedState
W/WifiMonitor(  967): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2030): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2030): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2030): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2030): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2030): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2030): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: DisconnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): Network connection established
D/wpa_supplicant( 2030): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2030): EAPOL authentication completed successfully
D/wpa_supplicant( 2030): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2030): nl80211: if_removed already cleared - ignore event
,D/WifiNative-wlan0(  967): doString: STATUS
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2030): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
I/WifiServiceExtension(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  967): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  967): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  967): invokeExitMethods: DisconnectedState
,D/KeyguardUpdateMonitor( 1146): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  967): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  967): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
D/WifiStateMachine(  967): handleMessage: X
D/BubblePopupHelper( 1146): isShowingBubblePopup : false
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
I/RemoteControlStatusBar( 1146): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  967): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@44efe2f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-12ms what=147462 obj=android.net.wifi.StateChangeResult@44ec6ff0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=147459
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-13ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196612
D/WifiStateMachine(  967): processMsg: ObtainingIpState
,D/WifiStateMachine(  967): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2030): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,V/DownloadManager( 4753): DownloadService onCreate
I/DownloadManager( 4753): in removeSpuriousFiles
,D/EAS     ( 4536): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4536): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/eas_req ( 4536): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4753): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428e0b78 on behalf of 4753
,I/DownloadManager( 4753): in trimDatabase
,V/DownloadManager( 4753): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428e2bc8 on behalf of 4753
,D/wpa_supplicant( 2030): wpa_driver_nl80211_driver_cmd OK len = 0, 2
V/DownloadManager( 4753): DownloadService onStartCommand
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  967): doBoolean: SET ps 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2030): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2030): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 2030): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
V/DownloadManager( 4753): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2030): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2030): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2030): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2030): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/LgeMiscReceiver( 4304): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4304): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428e6380 on behalf of 4753
D/WifiNative-wlan0(  967):    returned null
I/LgeMiscReceiver( 4304): networkInfo.isConnected() = false
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432d4fe0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432d4fe0 target=com.android.internal.util.StateMachine$SmHandler }
W/linker  ( 4536): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  967): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
D/HtmlEditor( 4536): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4536): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4536): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  967): handleMessage: X
I/dalvikvm( 4536): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4536): register_HtmlEditor, Success
D/HtmlEditor( 4536): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4536): register_HtmlEditorTimer, Success
D/HtmlEditor( 4536): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4536): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4536): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4536): register_HtmlEditorFont, Success
D/HtmlEditor( 4536): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4536): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4536): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
,V/DownloadManager( 4753): DownloadService onDestroy
D/HtmlEditor( 4536): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4536): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4536): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4536): JNI_OnLoad Success
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-11ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=196613
,D/WifiStateMachine(  967): processMsg: ObtainingIpState
D/WifiStateMachine(  967): ObtainingIpState{ when=-11ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
I/HubEmail( 4536): JNI_OnLoad()
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
,I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4790 uid=10052 gids={50052, 3003}
I/HubEmail( 4536): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4536): registerNatives()
I/HubEmail( 4536): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4536): registerNativeMethods()
I/HubEmail( 4536): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2030): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2030): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2030): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
W/Settings( 4536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  967):    returned true
,D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2030): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2030): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): DHCP successful
D/WifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  967): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  967): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState enter
D/WifiStateMachine(  967): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  967): handleMessage: X
D/KeyguardUpdateMonitor( 1146): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,W/WifiStateTracker(  967): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  967): 
W/WifiStateTracker(  967):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  967):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  399): Reading a NULL string not supported here.
D/WifiStateMachine(  967): handleMessage: E msg.what=135190
D/WifiStateMachine(  967): processMsg: VerifyingLinkState
D/WifiStateMachine(  967): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  967): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/BubblePopupHelper( 1146): isShowingBubblePopup : false
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  967): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState enter
D/WifiStateMachine(  967): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/RemoteControlStatusBar( 1146): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  967): handleMessage: X
D/HyLog   ( 4790): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4790): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4790): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1146): received broadcast android.net.wifi.STATE_CHANGE
D/BubblePopupHelper( 1146): isShowingBubblePopup : false
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/WifiStateMachine(  967): handleMessage: E msg.what=131092
D/WifiStateMachine(  967): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  967): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/RemoteControlStatusBar( 1146): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  967): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  967): transitionTo: destState=ConnectedState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  967): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,V/WfdStateTracker( 1162): handleWifiStateChangedEvent: 1
,D/KeyguardUpdateMonitor( 1146): received broadcast android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  967): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/ActivityManager(  967): Killing 3895:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
,E/Parcel  (  399): Reading a NULL string not supported here.
E/ActivityThread(  967): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=2 connState=1
,W/ActivityManager(  967): Failed to clear dns cache for: com.google.android.gms
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,I/RemoteControlStatusBar( 1146): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,V/        (  264): RouteController
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,V/LGRssiData( 4790): [loadRssi] File not exist 
,V/LGRssiData( 4790): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4790): [loadFeatureFromXml] *** start feature loading from xml
,V/        (  264): RouteController
,W/BaseRuntimeLoader( 4790): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,V/        (  264): RouteController
,W/BaseRuntimeLoader( 4790): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4790): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4790): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 4790): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4790): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4790): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 4790): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4790): onReceive CONNECTIVITY_CHANGE networkType=1
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4815 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  967): Killing 4290:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
,E/PhoneMonitor( 4790): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4790): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  264): RouteController
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,D/QCNEA   (  399): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  399): |CAC| updateWlanNetCfgInfo
,D/QCNEA   (  399): |CAC| updateNetCfgInfo
V/QCNEA   (  399): |CAC| *********************************************
V/QCNEA   (  399): |CAC|                   Netconfig               
V/QCNEA   (  399): |CAC| *********************************************
V/QCNEA   (  399): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  399): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  399): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  399): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  399): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  399): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  399): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  399): |CAC| *********************************************
D/QCNEA   (  399): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  399): |CAC| net type = 1
D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  399): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  399): |CAC| Received ssid= NG700
V/QCNEA   (  399): |CAC| 	ssid           =NG700
V/QCNEA   (  399): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  399): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  399): |CAC| *********************************************
D/QCNEA   (  399): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  399): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  399): |CAC| dispatchNetCfg: updating:0xb85808dc
D/QCNEA   (  399): |CAC| readCallback: read len:0, ret:-1, errno:11
I/CheckinService( 1972): Checking schedule, now: 1450233094422 next: 1450233037373
,D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
I/CheckinService( 1972): active receiver: enabled
D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4815): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4815): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,D/DhcpStateMachine(  967): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinService( 1972): Preparing to send checkin request
,I/EventLogService( 1972): Accumulating logs since 1450233004535
,I/CheckinRequestBuilder( 1972): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1972): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4844 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  967): Killing 4463:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4844): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4844): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4844): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2865): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  967): Killing 4496:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2865): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2865): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2865): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4857 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
D/LGDMClient( 2865): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2865): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2865): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4857): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4857): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4857): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4857): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4857): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4871 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  967): Killing 4522:com.lge.bnr/1000 (adj 15): empty #17
D/HyLog   ( 4871): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4871): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4871): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4871): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4871): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4871): intf.getDisplayName() = lo
I/Wireless_Storage( 4871): intf.getDisplayName() = sit0
I/Wireless_Storage( 4871): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4871): intf.getDisplayName() = teql0
I/Wireless_Storage( 4871): intf.getDisplayName() = wlan0
D/NFS     ( 4871): interface name:wlan0 name:wlan0
,D/NFS     ( 4871): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4871): interface name:wlan0 name:wlan0
D/NFS     ( 4871): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 4871): CONNECT : WIFI_CONNECT
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4896 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  967): Killing 4176:com.android.contacts/u0a21 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 21ms
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm(  967): GC_EXPLICIT freed 23370K, 49% free 29661K/57620K, paused 3ms+9ms, total 164ms
,D/HyLog   ( 4896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4896): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 1545): GC_EXPLICIT freed 1209K, 29% free 17821K/24832K, paused 1ms+3ms, total 25ms
,W/GAV2    ( 4896): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x42c6b9f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1972): awaiting user notification for token
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
V/WebViewChromium( 4896): Binding Chromium to the main looper Looper (main, tid 1) {428a5398}
I/chromium( 4896): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4896): Initializing chromium process, renderers=0
,W/chromium( 4896): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4896): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4896): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4896): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4896): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4896): Remote Branch: 
I/Adreno-EGL( 4896): Local Patches: 
I/Adreno-EGL( 4896): Reconstruct Branch: 
I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4935 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/DhcpStateMachine(  967): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  967): RunningState
D/HyLog   ( 4935): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4935): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4935): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4935): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4935): VFY: replacing opcode 0x60 at 0x000b
,I/NSApplication( 4896): Starting up...
D/dalvikvm( 4935): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4935): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4935): VFY: replacing opcode 0x62 at 0x005e
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
I/MultiDex( 4935): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4935): install
,I/MultiDex( 4935): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4935): loading existing secondary dex files
,I/ActivityManager(  967): Killing 4192:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/MultiDex( 4935): load found 3 secondary dex files
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/MultiDex( 4935): install done
D/WifiController(  967): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4722): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4722): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4722): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/dalvikvm( 4935): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4935): VFY: unable to resolve instance field 61
,D/dalvikvm( 4935): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4935): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4935): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4935): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4935): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4935): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4935): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4935): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4935): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
D/dalvikvm( 4935): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289f470
,I/QRemote ( 4722): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/dalvikvm( 4935): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289f470
,D/dalvikvm( 4935): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289f470, skipping init
D/QRemote ( 4722): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/dalvikvm( 4935): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289f470
D/dalvikvm( 4935): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289f470
V/JNIHelp ( 4935): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/QRemote ( 4722): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4687): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4687): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4722): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4722): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4722): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4722): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 4935): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4289f470
,D/dalvikvm( 4935): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4289f470
D/dalvikvm( 4935): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4289f470
,D/dalvikvm( 4935): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4289f470
,I/ProviderInstaller( 4935): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1545): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1545): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1972): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1880): callingUid 10006, callindPid: 1880
,E/MDM     ( 1427): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1972): Restart initialization of location
I/dalvikvm( 4935): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4935): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4935): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4935): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4935): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4935): VFY: replacing opcode 0x6e at 0x0201
,D/wpa_supplicant( 2030): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2030): EAPOL: disable timer tick
D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d95000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d95000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=1569624173
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GCM     ( 1545): Connected
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1545): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,D/dalvikvm( 4935): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42aa3798
,D/dalvikvm( 4935): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42aa3798
,D/dalvikvm( 4935): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42aa3798, skipping init
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  967): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 4935): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/dalvikvm( 4961): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4935): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4935): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 63ms
,I/Adreno-EGL( 4935): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4935): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4935): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4935): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4935): Remote Branch: 
I/Adreno-EGL( 4935): Local Patches: 
I/Adreno-EGL( 4935): Reconstruct Branch: 
,I/Adreno-EGL( 4935): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4935): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4935): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4935): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4935): Remote Branch: 
I/Adreno-EGL( 4935): Local Patches: 
I/Adreno-EGL( 4935): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 4935): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4935): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4935): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4935): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4935): Remote Branch: 
I/Adreno-EGL( 4935): Local Patches: 
I/Adreno-EGL( 4935): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 4935): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/jxcore-log( 4636): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4636): 
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=687818264
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1972): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  967): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): handleMessage: E msg.what=131212
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  967): send additional Connectivity Action
,D/LocSvc_java(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,D/WifiStateMachine(  967): handleMessage: X
D/QcConnectivityService(  967): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  967): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  967):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  967): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  967): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1452): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/CheckinTask( 1972): Sending checkin request (11619 bytes)
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1972): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1972): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x428be6d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1972): awaiting user notification for token
D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1972): Classify the device as Phone.
,I/CheckinTask( 1972): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1972): Checking schedule, now: 1450233096840 next: 1450810492837
,I/CheckinService( 1972): active receiver: disabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1229): Disconnected process message: 10
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!
,E/Parcel  (  399): Reading a NULL string not supported here.
,E/Parcel  (  399): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/WifiController(  967): battery changed pluggedType: 2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  967): battery changed pluggedType: 2
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3987): onReceive
,D/AppUp4:CustFacade( 3987): Context : android.app.ReceiverRestrictedContext@428ba650
D/AppUp4:CustFacade( 3987): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3987): isOpenOperator : true
,D/AppUp4:CustFacade( 3987): isPhone : true
,I/LicenseContentProvider( 2966): start selecting data
,D/SIMObserver( 2966): simInfo1
,I/AppUp4:EulaManager( 3987): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3987): begin check event
,I/AppUp4:CustModeStarterReceiver( 3987): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3987): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AppUp4:CustModeStarterReceiver( 3987): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 3987): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3987): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3987): handleAsyncCustNotification do not startCustService
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,V/DownloadManager( 4753): DownloadService onCreate
D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/DownloadManager( 4753): in removeSpuriousFiles
,V/DownloadManager( 4753): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4536): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4536): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428ec248 on behalf of 4753
,D/eas_req ( 4536): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4753): in trimDatabase
V/DownloadManager( 4753): DownloadService onStartCommand
,V/DownloadManager( 4753): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4753): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428ee0b8 on behalf of 4753
I/LgeMiscReceiver( 4304): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4304): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4304): networkInfo.isConnected() = false
,W/Settings( 4536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4790): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428efcb8 on behalf of 4753
,D/MobileConnectivityChangeReceiver( 4790): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4753): DownloadService onDestroy
,D/LGDMClient( 2865): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4857): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2865): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2865): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4871): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4871): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4857): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2865): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2865): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2865): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2865): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3987): onReceive
,D/AppUp4:CustFacade( 3987): Context : android.app.ReceiverRestrictedContext@428ba650
D/AppUp4:CustFacade( 3987): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3987): isOpenOperator : true
,D/AppUp4:CustFacade( 3987): isPhone : true
,I/LicenseContentProvider( 2966): start selecting data
,D/SIMObserver( 2966): simInfo1
,I/AppUp4:EulaManager( 3987): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3987): begin check event
,I/AppUp4:CustModeStarterReceiver( 3987): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4753): DownloadService onCreate
,I/DownloadManager( 4753): in removeSpuriousFiles
,D/EAS     ( 4536): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4536): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4753): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428f4be8 on behalf of 4753
,I/DownloadManager( 4753): in trimDatabase
V/DownloadManager( 4753): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4753): DownloadService onStartCommand
,V/DownloadManager( 4753): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428f73b0 on behalf of 4753
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428f7738 on behalf of 4753
I/LgeMiscReceiver( 4304): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4304): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4304): networkInfo.isConnected() = true
,D/PhoneState( 4304): setPdpRejectCasuse : false
,V/DownloadManager( 4753): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4790): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4790): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2865): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2865): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4857): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2865): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4871): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4871): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2865): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2865): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2865): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2865): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ContextImpl( 4857): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  967): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3987): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3987): onReceive
,D/AppUp4:CustFacade( 3987): Context : android.app.ReceiverRestrictedContext@428ba650
D/AppUp4:CustFacade( 3987): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3987): isOpenOperator : true
,D/AppUp4:CustFacade( 3987): isPhone : true
,I/LicenseContentProvider( 2966): start selecting data
,D/SIMObserver( 2966): simInfo1
,I/AppUp4:EulaManager( 3987): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3987): begin check event
,I/AppUp4:CustModeStarterReceiver( 3987): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4753): DownloadService onCreate
,I/DownloadManager( 4753): in removeSpuriousFiles
D/EAS     ( 4536): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4536): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4753): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428fbd68 on behalf of 4753
,I/DownloadManager( 4753): in trimDatabase
V/DownloadManager( 4753): DownloadService onStartCommand
V/DownloadManager( 4753): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4753): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428fdbd8 on behalf of 4753
,V/DownloadManager( 4753): created cursor android.database.sqlite.SQLiteCursor@428ff468 on behalf of 4753
I/LgeMiscReceiver( 4304): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4304): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4753): DownloadService onDestroy
I/LgeMiscReceiver( 4304): networkInfo.isConnected() = true
,D/PhoneState( 4304): setPdpRejectCasuse : false
,W/Settings( 4536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4790): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4790): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2865): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4857): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2865): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 4871): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4871): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2865): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4857): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2865): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2865): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2865): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2865): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,V/WifiServiceExtension(  967): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  967): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4896): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!,
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/Finsky  ( 4210): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4210): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): Killing 4555:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.460709 Y: -0.407364 Z: 9.756516 
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.460709 Y: -0.417374 Z: 9.759857 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.460709 .y:-0.407364 .z:9.756516
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.437973 Y: -0.406677 Z: 9.759048 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437973 .y:-0.406677 .z:9.759048
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5095 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,E/SlideAside( 3709): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3709): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/administrator(  967): Handling package changes for user 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  967): GC_EXPLICIT freed 2736K, 49% free 29818K/57620K, paused 25ms+8ms, total 119ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 5095): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5095): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5095): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/GlobalAccess( 1146): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1146): changeTargets() succeeded. size: 20
,D/WifiController(  967): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1427): DISABLE
,I/GCoreNlp( 1427): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 5095): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5095): MmsConfig.loadMmsSettings
I/MediaCodecList( 5095): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/Babel   ( 5095): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5095): MmsConfig.loadFromDatabase
I/MediaCodecList( 5095): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5095): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5095): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5095): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5095): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5095): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5095): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5095): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5095): MmsConfig.loadFromResources
E/Babel   ( 5095): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5095): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5095): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LocationProviderProxy(  967): applying state to connected service
,D/LocationProviderProxy(  967): applying state to connected service
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5095): [loadRssi] File not exist 
V/LGRssiData( 5095): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5095): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5095): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5095): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5095): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 3987): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3987): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 3987): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3987): onReceive
D/AppUp4:CustFacade( 3987): Context : android.app.ReceiverRestrictedContext@428ba650
D/AppUp4:CustFacade( 3987): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3987): isOpenOperator : true
,D/AppUp4:CustFacade( 3987): isPhone : true
I/LicenseContentProvider( 2966): start selecting data
,D/SIMObserver( 2966): simInfo1
,I/AppUp4:EulaManager( 3987): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3987): begin check event
D/AppUp4:Utils( 3987): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3987): Event For Nothing, skip.
,I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5144 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5144): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5144): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5144): BUILD Country: EU
,I/SystemConfig( 5144): BUILD Operator: OPEN
I/ActivityManager(  967): Killing 4687:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5161 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,I/SystemConfig( 5144): systemFeature RCS result false
,D/SystemConfig( 5144): refreshRcsSupport() :false
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5161): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5161): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5161): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  967): Killing 4722:com.lge.qremote/u0a96 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  967): Killing 4753:android.process.media/u0a23 (adj 15): empty #17
I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1972): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1972): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  967): Delaying start of: ServiceRecord{449d65a0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Icing   ( 1972): updateResources: need to parse f{com.google.android.gms}
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1972): GC_CONCURRENT freed 1878K, 22% free 19543K/24832K, paused 2ms+2ms, total 31ms
,I/IcingCorporaProvider( 2681): UpdateCorporaTask done [took 213 ms] updated apps [took 213 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/CaptivePortalTracker(  967): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/QcConnectivityService(  967): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  967): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  967): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  967): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  967): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  967): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  967): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/GAV4    ( 5095): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2030): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,I/PowerManagerService(  967): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  967): [updateScreenState] screen on = false
D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  967): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  967): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  967): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8933 usec
,D/qcom_sensors_hal(  967): hal_acquire_resources
,I/qcom_sensors_hal(  967): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  967): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  967): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  967): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  967): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  967): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  967): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  967): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457382 Y: -0.396805 Z: 9.778107 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457382 .y:-0.396805 .z:9.778107
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.473938 Y: -0.395935 Z: 9.780396 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.473938 .y:-0.395935 .z:9.780396
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/Sensors (  350): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  967): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  967): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  967): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  967): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  967): proximitySensorChanged  positive = true
I/KnockOnPowerController(  967): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.465424 Y: -0.403656 Z: 9.772583 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465424 .y:-0.403656 .z:9.772583
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.449539 Y: -0.404236 Z: 9.774811 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449539 .y:-0.404236 .z:9.774811
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.459900 Y: -0.394150 Z: 9.783386 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459900 .y:-0.394150 .z:9.783386
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.457993 Y: -0.392136 Z: 9.776886 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457993 .y:-0.392136 .z:9.776886
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  967): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@432085b8)
,D/KeyguardViewMediator( 1146): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1146): notifyScreenOnLocked
,D/KeyguardViewMediator( 1146): handleNotifyScreenOn
,D/KeyguardViewManager( 1146): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  967): **** SHOWN CALLED ****
I/WindowManager(  967): No lock screen! windowToken=null
,D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.467331 Y: -0.404984 Z: 9.780640 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467331 .y:-0.404984 .z:9.780640
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8d9e450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WifiStateMachine(  967): handleScreenStateChanged: true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131154
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2030): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2030): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131127
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131158
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  967): handleMessage: X
D/WifiServiceExtension(  967): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  967): handleMessage: E msg.what=132097
D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
D/WifiStateMachine(  967): processMsg: DriverStartedState
D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  967): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2030): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2030): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  967): handleMessage: X
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
,E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1162): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1162): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433f1870 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1162): enqueuing start. mLedList.size()=2
,D/qdlights( 1162): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1162): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1162): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1162): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1162): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1865): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 3:31:54
,E/SlideAside( 3709): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3709): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1865): 2 : This is isUpdating : false
,D/WeatherAncestor( 1865): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 3:31:54
,D/WeatherService( 1865): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1865): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1865): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.446487 Y: -0.393387 Z: 9.776260 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446487 .y:-0.393387 .z:9.776260
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.446182 Y: -0.397995 Z: 9.763809 
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446182 .y:-0.397995 .z:9.763809
D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1162): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1162): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1162): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1162): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1162): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1162): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1162): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1162): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1162): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in blankDisplay() while turning screen off: 430ms
D/qdlights( 1162): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1162): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1162): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1162): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 177, B = 177
,D/GlobalAccess( 1146): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1146): changeTargets() succeeded. size: 20
D/qdlights( 1162): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 171, B = 171
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233114762, nextTick: 5269, mDrawingTime: 1
,D/qdlights( 1162): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 165, B = 165
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1162): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1162): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1162): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 147, B = 147
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233114811, nextTick: 5219, mDrawingTime: 1
,D/qdlights( 1162): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1162): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 135, B = 135
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/qdlights( 1162): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1162): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 123, B = 123
D/WeatherService( 1865): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:31:54
,D/WeatherService( 1865): 2 : ACTION screen on
,D/WeatherService( 1865): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1162): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 117, B = 117
,D/WeatherService( 1865): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:31:54
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1162): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 111, B = 111
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
,E/Parcel  (  399): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/qdlights( 1162): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 105, B = 105
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1162): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 99, B = 99
V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/qdlights( 1162): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 93, B = 93
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  967): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  967): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1146): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1146): notifyScreenOffLocked
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qcom_sensors_hal(  967): hal_acquire_resources
D/qcom_sensors_hal(  967): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  967): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=1000
D/qdlights( 1162): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 87, B = 87
V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  967): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  967): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  967): hal_smgr_report_delete: Rcvd success response from request
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1162): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 81, B = 81
,V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,D/qdlights( 1162): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 75, B = 75
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/UsbSettings( 2613): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/KeyguardViewMediator( 1146): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  967): Vibrator off
V/UsbSettings( 2613): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
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
,D/WifiNative-wlan0(  967): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1162): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 69, B = 69
E/AudioSystem(  967): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2030): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2030): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  967): CMD_SCREEN_OFF 
D/WifiController(  967): shouldWifiStayAwake TRUE
I/EmotionalLed( 1162): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1162): clear
,D/qdlights( 1162): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 63, B = 63
,D/wpa_supplicant( 2030): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  967):    returned true
,D/WifiStateMachine(  967): handleMessage: X
,D/qdlights( 1162): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 57, B = 57
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{4297c5b8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/KeyguardViewMediator( 1146): handleNotifyScreenOff
D/KeyguardViewManager( 1146): onScreenTurnedOff()
E/CliptrayService( 1162): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
D/qdlights( 1162): set_light_notifications: 2,ff003333,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 51, B = 51
I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
,D/WeatherService( 1865): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:31:55
,D/WeatherService( 1865): 2 : ACTION screen off
,D/WeatherService( 1865): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:31:55
D/qdlights( 1162): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 45, B = 45
,V/TelephonyAutoProfiling(  967): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
E/Parcel  (  399): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1452): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1452): Emergency Service
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1452): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1452): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_roaming_state, value : null
D/qdlights( 1162): set_light_notifications: 2,ff002727,10,0,2
D/qdlights( 1162): [Current] = 255, R = 0, G = 39, B = 39
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1452): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/PhoneApp( 1452): Action intent recieved:android.intent.action.SCREEN_OFF
D/NfcService( 1477): NFC-C OFF
,D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/qdlights( 1162): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 33, B = 33
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1162): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1162): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1162): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1162): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1162): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1162): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1162): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1162): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  350): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiStateMachine(  967): handleMessage: X
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1146): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/PhoneApp( 1452): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1146): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1146): OMADM Lock is OFF
,D/KeyguardViewMediator( 1146): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1146): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233120050, nextTick: 59968, mDrawingTime: 5
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233120061, nextTick: 59972, mDrawingTime: 0
,I/VacuumService( 1545): Vacuum at: now=1450233123975 tag=VacuumService
,I/GoogleURLConnFactory( 1545): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1545): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1545): GC_CONCURRENT freed 1789K, 28% free 18025K/24832K, paused 4ms+4ms, total 70ms
,W/Uploader( 1545):  no longer exists, so no auth token.
,W/Uploader( 1545): No account for auth token provided
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233132696547191; DSPS: 5268737; Offset: 1450232971907454174
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1229): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1162): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233152698116922; DSPS: 5924148; Offset: 1450232971907467508
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233172699699050; DSPS: 6579560; Offset: 1450232971907462722
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233180056, nextTick: 59970, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233180060, nextTick: 59972, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233192701693990; DSPS: 7234985; Offset: 1450232971907474020
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233212703172993; DSPS: 7890394; Offset: 1450232971907457661
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233232704986058; DSPS: 8545813; Offset: 1450232971907470189
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233240048, nextTick: 59979, mDrawingTime: 3
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233240051, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233252706662405; DSPS: 9201228; Offset: 1450232971907468070
,I/jxcore-log( 4636): Connected to the server!
I/jxcore-log( 4636): 
,I/chromium( 4636): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233272708020262; DSPS: 9856633; Offset: 1450232971907452636
,D/wpa_supplicant( 2030): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 8 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 9 BSSID fc:6f:b7:3e:78:0a SSID 'UPC249917252' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2030): wlan0: BSS: Remove id 10 BSSID 64:7c:34:95:11:85 SSID 'Chopin_143' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2030): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 a0:c5:62:7a:49:96]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 fc:6f:b7:3e:78:0a]
,D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 64:7c:34:95:11:85]
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233292709799890; DSPS: 10512051; Offset: 1450232971907462244
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233300044, nextTick: 59961, mDrawingTime: 10
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233300062, nextTick: 59968, mDrawingTime: 1
,I/EventLogService( 1972): Aggregate from 1450233094464 (log), 1450231455395 (data)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 2669): GC_CONCURRENT freed 7668K, 33% free 16866K/24832K, paused 3ms+1ms, total 34ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  967): updateLightListLocked :r=NotificationRecord(0x432a2198: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  967): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4210): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4210): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4210): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4210): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4210): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4210): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4210): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4210): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4210): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4210): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233312711401288; DSPS: 11167463; Offset: 1450232971907476728
,I/LocationManagerService(  967): remove 43320770
,D/LocationManagerService(  967): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2669): GC_CONCURRENT freed 1598K, 31% free 17315K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2669): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Mlt MonitorService( 2669): parseLastkmsg to dump
,D/dalvikvm( 2669): GC_CONCURRENT freed 1630K, 29% free 17632K/24832K, paused 3ms+2ms, total 44ms
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233332713248415; DSPS: 11822884; Offset: 1450232971907462283
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233352714361012; DSPS: 12478280; Offset: 1450232971907476247
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233360035, nextTick: 59978, mDrawingTime: 10
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233360070, nextTick: 59961, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233372716507776; DSPS: 13133711; Offset: 1450232971907456263
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233392717814331; DSPS: 13789113; Offset: 1450232971907481080
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233412719339167; DSPS: 14444523; Offset: 1450232971907480037
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233420052, nextTick: 59972, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233420056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233432721161659; DSPS: 15099943; Offset: 1450232971907471474
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233452722454152; DSPS: 15755346; Offset: 1450232971907451711
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233472724138362; DSPS: 16410761; Offset: 1450232971907457454
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233480058, nextTick: 59971, mDrawingTime: 3
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233480059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233492725755490; DSPS: 17066174; Offset: 1450232971907457151
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233512727451004; DSPS: 17721589; Offset: 1450232971907474198
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1146): handleBatteryUpdate (2) (100)
D/WifiController(  967): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1146): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1229): Disconnected process message: 10
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233532728781465; DSPS: 18376993; Offset: 1450232971907461885
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233540041, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233540047, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233552730332029; DSPS: 19032404; Offset: 1450232971907456053
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233572732161710; DSPS: 19687824; Offset: 1450232971907454679
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233592733713056; DSPS: 20343234; Offset: 1450232971907480146
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233600052, nextTick: 59965, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233600062, nextTick: 59968, mDrawingTime: 1
,I/ActivityManager(  967): Killing 4536:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233612734923882; DSPS: 20998634; Offset: 1450232971907470269
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233632736785333; DSPS: 21654055; Offset: 1450232971907470148
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233652738326367; DSPS: 22309466; Offset: 1450232971907454785
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233660048, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233660051, nextTick: 59977, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233672740199172; DSPS: 22964887; Offset: 1450232971907466018
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233692741775726; DSPS: 23620299; Offset: 1450232971907455658
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233712743497541; DSPS: 24275715; Offset: 1450232971907468489
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233720049, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233720059, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233732745896285; DSPS: 24931154; Offset: 1450232971907456344
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233752747544662; DSPS: 25586568; Offset: 1450232971907456772
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233772749133717; DSPS: 26241980; Offset: 1450232971907458913
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233780047, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233780051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233792750990324; DSPS: 26897400; Offset: 1450232971907484465
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233812752394066; DSPS: 27552806; Offset: 1450232971907484399
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233832753964475; DSPS: 28208218; Offset: 1450232971907467893
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233840046, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233840057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233852756381082; DSPS: 28863657; Offset: 1450232971907473612
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233872757987637; DSPS: 29519070; Offset: 1450232971907462735
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233892759587317; DSPS: 30174482; Offset: 1450232971907475501
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233900045, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233900050, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233912761305903; DSPS: 30829898; Offset: 1450232971907485103
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233932762727354; DSPS: 31485305; Offset: 1450232971907472228
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233952764655523; DSPS: 32140728; Offset: 1450232971907477789
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233960051, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450233960057, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233972767019682; DSPS: 32796166; Offset: 1450232971907461577
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450233992768770352; DSPS: 33451583; Offset: 1450232971907472745
,D/GCM     ( 1545): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234012770380084; DSPS: 34106996; Offset: 1450232971907465045
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234020043, nextTick: 59966, mDrawingTime: 9
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234020058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234032771995909; DSPS: 34762409; Offset: 1450232971907463439
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234052773809183; DSPS: 35417828; Offset: 1450232971907476176
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234072775537613; DSPS: 36073245; Offset: 1450232971907465104
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234080046, nextTick: 59978, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234080051, nextTick: 59977, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234092777552500; DSPS: 36728671; Offset: 1450232971907465831
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234112779138014; DSPS: 37384083; Offset: 1450232971907464431
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234132780785298; DSPS: 38039497; Offset: 1450232971907463765
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234140044, nextTick: 59976, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234140051, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234152782342947; DSPS: 38694908; Offset: 1450232971907465018
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234172787721169; DSPS: 39350444; Offset: 1450232971907472146
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234192793337462; DSPS: 40005988; Offset: 1450232971907473205
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234200043, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234200063, nextTick: 59967, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234212795178965; DSPS: 40661408; Offset: 1450232971907483653
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234232797054948; DSPS: 41316830; Offset: 1450232971907467546
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234252798609731; DSPS: 41972241; Offset: 1450232971907465933
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234260047, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234260054, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234272800433891; DSPS: 42627661; Offset: 1450232971907459038
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234292801749716; DSPS: 43283064; Offset: 1450232971907462607
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234312803075021; DSPS: 43938467; Offset: 1450232971907475656
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234320045, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234320048, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234332804919232; DSPS: 44593888; Offset: 1450232971907458295
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234352806791829; DSPS: 45249309; Offset: 1450232971907469320
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234372808097811; DSPS: 45904712; Offset: 1450232971907463046
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234380047, nextTick: 59975, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234380054, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234392809202699; DSPS: 46560108; Offset: 1450232971907469301
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234412810503941; DSPS: 47215511; Offset: 1450232971907458287
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234432812305913; DSPS: 47870930; Offset: 1450232971907459722
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234440040, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234440046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234452814170124; DSPS: 48526351; Offset: 1450232971907462361
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234472816240794; DSPS: 49181779; Offset: 1450232971907457836
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234492817836307; DSPS: 49837191; Offset: 1450232971907466434
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234500061, nextTick: 59967, mDrawingTime: 3
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234500064, nextTick: 59964, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234512819666091; DSPS: 50492611; Offset: 1450232971907465164
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234532821469990; DSPS: 51148030; Offset: 1450232971907468526
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234552823144982; DSPS: 51803445; Offset: 1450232971907465051
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234560040, nextTick: 59968, mDrawingTime: 9
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234560057, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234572824964296; DSPS: 52458865; Offset: 1450232971907453310
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234592826973613; DSPS: 53114290; Offset: 1450232971907478985
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234612828764542; DSPS: 53769709; Offset: 1450232971907469376
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234620036, nextTick: 59981, mDrawingTime: 8
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234620044, nextTick: 59984, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234632830541149; DSPS: 54425127; Offset: 1450232971907475964
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234652832188850; DSPS: 55080541; Offset: 1450232971907475716
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234672834005509; DSPS: 55735961; Offset: 1450232971907461320
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234680043, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234680049, nextTick: 59980, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234692835385085; DSPS: 56391366; Offset: 1450232971907467605
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234712836914817; DSPS: 57046776; Offset: 1450232971907471458
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234732838523090; DSPS: 57702189; Offset: 1450232971907462299
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234740048, nextTick: 59964, mDrawingTime: 9
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234740062, nextTick: 59969, mDrawingTime: 1
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234752840338447; DSPS: 58357608; Offset: 1450232971907477119
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234772841892814; DSPS: 59013019; Offset: 1450232971907475090
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234792843658431; DSPS: 59668437; Offset: 1450232971907470687
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234800082, nextTick: 59947, mDrawingTime: 4
,I/ProcessStatsService(  967): Prepared write state in 66ms
D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234800085, nextTick: 59946, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  967): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-16-04.bin
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  967): GC_CONCURRENT freed 3234K, 49% free 29857K/57620K, paused 25ms+13ms, total 217ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234812846185664; DSPS: 60323880; Offset: 1450232971907464961
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234832847982323; DSPS: 60979299; Offset: 1450232971907461083
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234852849500857; DSPS: 61634708; Offset: 1450232971907484256
,D/KeyguardUpdateMonitor( 1146): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1146): handleTimeUpdate
,D/KeyguardModel( 1146): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234860037, nextTick: 59972, mDrawingTime: 9
,D/Clock   ( 1146): Clock updated, drawingStartTime : 1450234860053, nextTick: 59974, mDrawingTime: 2
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234872851102724; DSPS: 62290121; Offset: 1450232971907468691
,D/qcom_sensors_hal(  967): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  967): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  967): hal_ts_offset_is: Apps: 1450234892852686727; DSPS: 62945533; Offset: 1450232971907465780
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  967): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  967): Done.
,D/QcConnectivityService(  967): Setting timer for 720seconds
,D/LocationManagerService(  967): getAllProviders()=[passive, gps, network]
,D/GCM     ( 1545): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  967): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,D/BubblePopupHelper( 1146): isShowingBubblePopup : false
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  967): Killing 4896:com.google.android.apps.magazines/u0a104 (adj 15): empty for 1801s
I/ActivityManager(  967): Killing 4871:com.lge.wireless_storage/u0a101 (adj 15): empty for 1801s
I/ActivityManager(  967): Killing 4857:com.lge.lgdmsgcm/1000 (adj 15): empty for 1801s
I/ActivityManager(  967): Killing 4844:com.lge.drmservice/u0a66 (adj 15): empty for 1801s
I/ActivityManager(  967): Killing 4815:com.android.chrome/u0a63 (adj 15): empty for 1801s
I/ActivityManager(  967): Killing 4790:com.google.android.setupwizard/u0a52 (adj 15): empty for 1801s
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{43335ff8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/AndroidRuntime( 6960): 
D/AndroidRuntime( 6960): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6960): CheckJNI is OFF
D/dalvikvm( 6960): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6960): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6960): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6960): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6960): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 6960): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 6960): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6960): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 6960): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
I/ActivityManager(  967): Killing 4636:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  967): Killing 4935:com.google.android.gms.unstable/u0a6 (adj 15): empty for 1804s
I/ActivityManager(  967):   Force finishing activity ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  967): moveHomeStack:
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} (in existing)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1}
D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{44c4ac98 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
I/WindowState(  967): WIN DEATH: Window{43e0be80 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  967): Client connection lost with reason: 4
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/PackageSettings(  967): Skipping PackageSetting{42d57f78 com.example.hello/10312} due to missing metadata
I/ActivityManager(  967): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: some activity pausing.
I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
D/KeyguardModel( 1146): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/SlideAside( 3709): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3709): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
D/AppUp4:Utils( 3987): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 3987): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 3987):  isExcludedPackage  packagename = com.test.thalitest
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/PhoneApp( 1452): getIsInUseVoLTE : false
W/System.err( 2669): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2669): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2669): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2669): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2669): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2669): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2669): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2669): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2669): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2669): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2669): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2669): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2669): 	at dalvik.system.NativeStart.main(Native Method)
W/GeofencerStateMachine( 1427): Ignoring removeGeofence because network location is disabled.
D/AppUp4  ( 3987):  isExcludedPackage TRUE : com.test.thalitest
I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6991 uid=10090 gids={50090}
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
D/dalvikvm( 2681): GC_EXPLICIT freed 4104K, 28% free 17919K/24832K, paused 2ms+2ms, total 46ms
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  967): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7004 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
W/ActivityManager(  967): getAssistContextExtras failed: no resumed activity
D/GlobalAccess( 1146): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1146): changeTargets() succeeded. size: 20
D/KeyguardModel( 1146): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
D/dalvikvm(  967): GC_EXPLICIT freed 1395K, 48% free 29739K/56948K, paused 5ms+9ms, total 119ms
D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 97ms
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} (pause complete)
D/HyLog   ( 6991): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6991): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6991): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7004): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7004): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7004): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "sms"
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
D/administrator(  967): Handling package changes for user 0
I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "smsto"
W/Binder  ( 1316): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1316): java.lang.NullPointerException
W/Binder  ( 1316): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1316): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1316): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1316): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputMethodManagerService(  967): IME STATUS OFF
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4636 uid 10304
D/[BNRAppListMgrReceiver]( 7004): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mms"
I/LockScreenSettings( 6991): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  967): Killing 5095:com.google.android.talk/u0a77 (adj 15): empty for 1801s
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/KeyguardModel( 1146): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1146): createShortcutInfo...
D/KeyguardModel( 1146): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1146): createShortcutInfo...
D/KeyguardModel( 1146): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1146): createShortcutInfo...
D/KeyguardModel( 1146): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1146): createShortcutInfo...
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/VoicemailCleanupService( 1819): Cleaning up data for package: com.test.thalitest
D/KeyguardModel( 1146): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1146): createShortcutInfo...
D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
I/InteractionManagerConfigurator(  967): com.test.thalitest isn't inclued in dragdropPackageList
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10304 #1
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{42cb1788 u0 com.lge.launcher2/.Launcher t1} time:1930119
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7020 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/KeyguardModel( 1146): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1146): createShortcutInfo...
D/KeyguardModel( 1146): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1146): createShortcutInfo...
D/KeyguardModel( 1146): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1146): createShortcutInfo...
D/KeyguardModel( 1146): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1146): createShortcutInfo...
D/KeyguardModel( 1146): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1146): createShortcutInfo...
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 7020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7020): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7020): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm( 1490): GC_CONCURRENT freed 5664K, 9% free 60779K/66628K, paused 2ms+3ms, total 24ms
D/dalvikvm( 1490): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/dalvikvm(  967): GC_EXPLICIT freed 476K, 48% free 29770K/56948K, paused 5ms+17ms, total 208ms
D/dalvikvm( 1146): GC_CONCURRENT freed 6195K, 10% free 69095K/76588K, paused 13ms+5ms, total 46ms
D/dalvikvm( 1146): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/LGEmail ( 7020): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/LGEmail ( 7020): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
D/AndroidRuntime( 6960): Shutting down VM
D/dalvikvm( 6960): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
D/KeyguardModel( 1146): handleShortcutListChanged...
D/KeyguardModel( 1146): handleShortcutListChanged...
I/ActivityManager(  967): Killing 5161:com.android.gallery3d/u0a27 (adj 15): empty for 1801s
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
W/BaseRuntimeLoader( 7020): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7020): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7020): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7020): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageChangeReceiver( 7020): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7041 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/ActivityManager(  967): Killing 3867:com.google.android.apps.plus/u0a112 (adj 15): empty for 1801s
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/HyLog   ( 7041): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7041): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7041): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
I/[LGHome]Launcher( 1490): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@428a0058 time:1930389
D/PackageIntentReceiver( 2613): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2613): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2613): Delete mPackageMame : com.test.thalitest
I/ActivityManager(  967): Killing 4210:com.android.vending/u0a50 (adj 15): empty for 1801s
I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  967): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7058 uid=10073 gids={50073, 3003, 1028, 1015}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 7058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7058): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7058): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/SQLiteLog( 2681): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 2681): threadid=14: thread exiting with uncaught exception (group=0x41862e48)
E/AndroidRuntime( 2681): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2681): Process: com.google.android.googlequicksearchbox:search, PID: 2681
E/AndroidRuntime( 2681): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 2681): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 2681): 	at cau.d(PG:186)
E/AndroidRuntime( 2681): 	at cea.g(PG:591)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:299)
E/AndroidRuntime( 2681): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 2681): 	at android.content.ContentResolver.update(ContentResolver.java:1332)
E/AndroidRuntime( 2681): 	at ceb.OV(PG:906)
E/AndroidRuntime( 2681): 	at ced.sV(PG:823)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1267)
E/AndroidRuntime( 2681): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1200)
E/AndroidRuntime( 2681): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2681): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2681): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2681): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2681): Sending signal. PID: 2681 SIG: 9
E/DropBoxManagerService(  967): Can't write: system_app_crash
E/DropBoxManagerService(  967): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  967): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  967): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  967): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  967): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  967): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  967): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  967): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  967): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  967): 	... 5 more
E/SQLiteLog( 2669): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2669): Error inserting f006=-1 f003= f002=1450234906748 f005=2681 f004=20
E/SQLiteDatabase( 2669): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2669): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2669): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2669): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2669): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2669): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2669): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2669): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2669): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2669): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2669): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2669): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2669): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2669): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2669): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2669): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)
I/ActivityManager(  967): Process com.google.android.googlequicksearchbox:search (pid 2681) has died.
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  967): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42d02c38 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Going to sleep and all paused
D/WifiService(  967): Client connection lost with reason: 4

```
