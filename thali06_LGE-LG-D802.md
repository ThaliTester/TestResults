#### Test 50650278b44f053_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
I/dalvikvm( 1966): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1966): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1966): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
W/BaseAppContext( 1966): Using Auth Proxy for data requests.
,W/GAV2    ( 4609): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  965): Killing 4098:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1966): GC_CONCURRENT freed 1749K, 22% free 19395K/24832K, paused 3ms+3ms, total 30ms
D/dalvikvm( 1966): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 1966): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ConfigFetchService( 1966): fetch service done; releasing wakelock
I/ConfigFetchService( 1966): stopping self
D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4653): 
D/AndroidRuntime( 4653): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4653): CheckJNI is OFF
D/dalvikvm( 4653): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4653): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4653): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4653): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4653): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4653): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1966): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1966): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4653): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4653): failed to load memtrack module: -2
I/Icing   ( 1966): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4653): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4653
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (193 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{43b42f60 stackId=1, 2 tasks}
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
D/AndroidRuntime( 4653): Shutting down VM
D/dalvikvm( 4653): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3757): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/UsbSettingsControl( 2583): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2583): [AUTORUN] onPause() : mActiveCurrentFunction = boot
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4683 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3757): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3757): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4683): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4683): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4683): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/WebViewChromium( 4683): Binding Chromium to the background looper Looper (main, tid 1) {430508d8}
I/chromium( 4683): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4683): Initializing chromium process, renderers=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/chromium( 4683): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4683): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4683): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4683): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4683): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4683): Remote Branch: 
I/Adreno-EGL( 4683): Local Patches: 
I/Adreno-EGL( 4683): Reconstruct Branch: 
D/WifiController(  965): battery changed pluggedType: 2
I/dalvikvm( 4683): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4683): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4683): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4683): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4683): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4683): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4683): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4683): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4683): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4683): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4683): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4683): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4683): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4683): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4683): Enabling debug mode 0
,W/AwContents( 4683): nativeOnDraw failed; clearing to background color.
,W/AwContents( 4683): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  965): IME STATUS OFF
,I/ActivityManager( 4683): Timeline: Activity_idle id: android.os.BinderProxy@43051fb8 time:110901
,I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +376ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/JsMessageQueue( 4683): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4683): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x43056098
,D/dalvikvm( 4683): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x43056098
,D/jxcore_app_log( 4683): JniHelper::setJavaVM(0x42007808), pthread_self() = 1636289336
,D/JX-Cordova( 4683): jxcore cordova android initializing
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3} time:111288
D/ActivityManager(  965): no-history finish of ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{435b56e0 ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,D/UsbSettings( 2583): [AUTORUN] onStop()
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4683): GC_CONCURRENT freed 2810K, 13% free 21842K/24832K, paused 2ms+1ms, total 44ms
D/dalvikvm( 4683): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 4683): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 4683): GC_FOR_ALLOC freed 170K, 12% free 21862K/24832K, paused 30ms, total 30ms
D/dalvikvm( 4683): GC_FOR_ALLOC freed 201K, 12% free 21879K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4683): Grow heap (frag case) to 23.677MB for 144892-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4683): GC_FOR_ALLOC freed 257K, 13% free 21926K/24976K, paused 24ms, total 24ms
I/dalvikvm-heap( 4683): Grow heap (frag case) to 23.792MB for 217334-byte allocation
D/dalvikvm( 4683): GC_FOR_ALLOC freed 369K, 13% free 22000K/25192K, paused 22ms, total 22ms
I/dalvikvm-heap( 4683): Grow heap (frag case) to 23.968MB for 325996-byte allocation
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2018): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/dalvikvm( 4683): GC_FOR_ALLOC freed 570K, 14% free 22121K/25512K, paused 24ms, total 24ms
I/dalvikvm-heap( 4683): Grow heap (frag case) to 24.243MB for 488990-byte allocation
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 4683): GC_FOR_ALLOC freed 868K, 15% free 22298K/25992K, paused 23ms, total 23ms
I/dalvikvm-heap( 4683): Grow heap (frag case) to 24.649MB for 733480-byte allocation
D/dalvikvm( 4683): GC_FOR_ALLOC freed 1290K, 16% free 22556K/26712K, paused 24ms, total 24ms
D/dalvikvm( 4683): GC_CONCURRENT freed 1676K, 15% free 22927K/26712K, paused 1ms+4ms, total 47ms
D/dalvikvm( 4683): WAIT_FOR_CONCURRENT_GC blocked 36ms
D/dalvikvm( 4683): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 4683): GC_FOR_ALLOC freed 378K, 15% free 22885K/26712K, paused 23ms, total 23ms
I/dalvikvm-heap( 4683): Grow heap (frag case) to 26.096MB for 1650320-byte allocation
D/dalvikvm( 4683): GC_CONCURRENT freed 1798K, 18% free 23476K/28324K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 4683): GC_FOR_ALLOC freed 1279K, 17% free 23526K/28324K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 27.509MB for 2475476-byte allocation
,D/dalvikvm( 4683): GC_CONCURRENT freed 360K, 16% free 25875K/30744K, paused 2ms+2ms, total 43ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4683): GC_FOR_ALLOC freed 4265K, 21% free 24501K/30744K, paused 33ms, total 39ms
I/dalvikvm-heap( 4683): Grow heap (frag case) to 29.641MB for 3713210-byte allocation
D/dalvikvm( 4683): GC_CONCURRENT freed 2862K, 26% free 25478K/34372K, paused 3ms+5ms, total 36ms
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 4683): GC_FOR_ALLOC freed 621K, 26% free 25463K/34372K, paused 43ms, total 45ms
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.465897 Y: -0.410446 Z: 9.754913 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465897 .y:-0.410446 .z:9.754913
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
W/jxcore-log( 4683): Initializing JXcore engine
W/jxcore-log( 4683): JXcore engine is ready
D/dalvikvm( 4683): GC_CONCURRENT freed 360K, 19% free 28101K/34372K, paused 2ms+1ms, total 29ms
D/dalvikvm( 4683): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 4683): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/jxcore-log( 4683): Starting JXcore engine
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.463989 Y: -0.403244 Z: 9.757950 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463989 .y:-0.403244 .z:9.757950
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/jxcore-log( 4683): Platform android
W/jxcore-log( 4683): 
W/jxcore-log( 4683): Process ARCH arm
W/jxcore-log( 4683): 
,I/jxcore-log( 4683): JXcore Cordova bridge is ready!
I/jxcore-log( 4683): 
,W/jxcore-log( 4683): JXcore engine is started
,I/chromium( 4683): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/chromium( 4683): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
I/chromium( 4683): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/GAV2    ( 4609): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/jxcore-log( 4683): Toggling radios to true
I/jxcore-log( 4683): 
,D/BluetoothManagerService(  965): Message: 20
,D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@450ee318:true
,D/BluetoothAdapter( 4683): enable(): BT is already enabled..!
,D/WifiStateMachine(  965): handleMessage: E msg.what=131145
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doBoolean: DISCONNECT
,I/jxcore-log( 4683): Radios toggled
I/jxcore-log( 4683): 
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2018): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2018): wlan0: Cancelling scan request
D/wpa_supplicant( 2018): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2018): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2018): TDLS: Tear down peers
,D/wpa_supplicant( 2018): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4683): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4683): 
D/WifiService(  965): New client listening to asynchronous messages
D/WifiService(  965): setWifiEnabled: true pid=4683, uid=10304
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  965): disconnect pid=4683, uid=10304
,D/WifiService(  965): reconnect pid=4683, uid=10304
I/jxcore-log( 4683): Perf Test app loaded loaded
I/jxcore-log( 4683): 
I/Choreographer( 4683): Skipped 60 frames!  The application may be doing too much work on its main thread.
,D/wpa_supplicant( 2018): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2018): wlan0: Deauthentication notification
D/wpa_supplicant( 2018): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2018): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2018): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2018): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2018): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2018): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2018): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7789d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2018):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2018): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2018): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2018): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2018): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2018): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2018): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2018): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2018): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2018): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2018): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2018): nl80211: Event message available
D/wpa_supplicant( 2018): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 2018): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  965): invokeExitMethods: ConnectedState
,W/Settings(  965): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  965): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131146
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiNative-wlan0(  965): doBoolean: RECONNECT
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2018): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2018): Fast associate: Old scan results
D/wpa_supplicant( 2018): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2018): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2018): wlan0: nl80211: scan request
D/wpa_supplicant( 2018): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2018): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2018): nl80211: Event message available
D/wpa_supplicant( 2018): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2018): wlan0: nl80211: Scan trigger
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: DisconnectingState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147460
D/WifiStateMachine(  965): processMsg: DisconnectingState
I/jxcore-log( 4683): check test folder
I/jxcore-log( 4683): 
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection lost
D/WifiStateMachine(  965): Stopping DHCP and clearing IP
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2018): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2018): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2018): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2018): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2018): wpa_driver_nl80211_driver_cmd OK len = 0, 2
I/jxcore-log( 4683): found test : ./testFindPeers.js
I/jxcore-log( 4683): 
D/WifiNative-wlan0(  965):    returned true
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/DhcpStateMachine(  965): RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  965): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  965): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= 
D/QCNEA   (  596): |CAC| net type = 3
V/QCNEA   (  596): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  596): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8f0b8dc
,D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED,
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiHS20(  965): hidePasspointNotification off =false
,D/QcConnectivityService(  965): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/jxcore-log( 4683): found test : ./testSendData.js
I/jxcore-log( 4683): 
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
D/QcConnectivityService(  965): Attempting to switch to mobile
D/QcConnectivityService(  965): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
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
,D/WifiStateMachine(  965): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4737 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  965): handleMessage: E msg.what=131213
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
,D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/NetworkManagementService(  965): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/HyLog   ( 4737): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4737): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4737): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 4737): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/NetworkManagementService(  965): route cmd failed: 
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
,D/NetUtils(  965): android_net_utils_resetConnections in env=0x5c7c6690 clazz=0x6c900001 iface=wlan0 mask=0x3
D/PCSuite ( 4737): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4737): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/QcConnectivityService(  965): resetConnections(wlan0, 3)
,V/NativeCrypto( 1545): Read error: ssl=0x63aa12c8: I/O error during system call, Connection timed out
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4771 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  965): Killing 4191:com.google.android.talk/u0a77 (adj 15): empty #17
,V/NativeCrypto( 1545): SSL shutdown failed: ssl=0x63aa12c8: I/O error during system call, Broken pipe
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4771): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4771): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4771): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=false
I/chromium( 4683): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  965): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,D/QRemote ( 4771): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4771): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4771): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4771): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4771): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4771): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4771): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4771): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  965): Killing 2130:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  965): StoppedState
,D/dalvikvm(  965): GC_CONCURRENT freed 1049K, 49% free 29656K/57676K, paused 3ms+6ms, total 86ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1545): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4306e0c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
D/wpa_supplicant( 2018): nl80211: Event message available
D/wpa_supplicant( 2018): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2018): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2018): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2018): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 2018): nl80211: Survey data missing
D/wpa_supplicant( 2018): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2018): wlan0: BSS: Add new id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Add new id 7 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432'
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 2018): wlan0: New scan results available
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2018): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2018): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2018): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 2018): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 2018): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2018): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2018): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2018): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2018): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2018): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2018): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-47 wps
D/wpa_supplicant( 2018): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2018): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2018): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2018): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2018): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2018): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2018): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2018): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2018): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2018): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2018): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb778b5a8  current_ssid=0x0
D/wpa_supplicant( 2018): scard is not null..
D/wpa_supplicant( 2018): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2018): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2018): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2018): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2018): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2018): wlan0: [MDM] lg mdm allow,/disallow auto connect is not set 
D/wpa_supplicant( 2018): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2018): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2018): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2018): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2018): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2018): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2018): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2018): wlan0: Cancelling scan request
D/wpa_supplicant( 2018): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2018): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2018): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2018): RSN: PMKSA cache search - network_ctx=0xb778b5a8 try_opportunistic=0
D/wpa_supplicant( 2018): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2018): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2018): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2018): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2018): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2018): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2018): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2018): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2018): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2018): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2018): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2018): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2018): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2018): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2018): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2018): nl80211: Unsubscribe mgmt frames handle 0xb778a590 (mode change)
D/wpa_supplicant( 2018): nl80211: Subscribe to mgmt frames with non-AP handle 0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2018): nl80211: Register frame type=0xd0 nl_handle=0xb778a590
D/wpa_supplicant( 2018): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2018): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2018):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018):   * freq=2412
D/wpa_supplicant( 2018):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2018):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2018):   * Auth Type 0
D/wpa_supplicant( 2018):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 9e:93:4e:3e:ba:c5]
D/wpa_supplicant( 2018): nl80211: Connect request send successfully
D/wpa_supplicant( 2018): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2018): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2018): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2018): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2018): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 64:7c:34:b0:03:6e]
D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2018): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity
D/wpa_supplicant( 2018): nl80211: Event message available
D/wpa_supplicant( 2018): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2018): nl80211: Connect event
D/wpa_supplicant( 2018): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2018): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2018): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2018): wlan0: Association info event
D/wpa_supplicant( 2018): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2018): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2018): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2018): wlan0: freq=2412 MHz
D/wpa_supplicant( 2018): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2018): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2018): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2018): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2018): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2018): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): scard is not null..
D/wpa_supplicant( 2018): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2018): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2018): TDLS: Remove peers on association
D/wpa_supplicant( 2018): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2018): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2018): EAPOL: enable timer tick
D/wpa_supplicant( 2018): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2018): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2018): wlan0: Cancelling scan request
D/wpa_supplicant( 2018): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2018): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2018): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2018): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2018): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2018): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2018): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2018): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2018): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2018): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/wpa_supplicant( 2018): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 77 dd 20 d0 bc f0 77 c4 b8 50 3d f9 02 93 33 ...
D/wpa_supplicant( 2018): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2018): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2018): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2018): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2018): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2018):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2018):   key_nonce - hexdump(len=32): 77 dd 20 d0 bc f0 77 c4 b8 50 3d f9 02 93 33 e0 be 41 c6 dd 6c 23 38 05 0b 8c ee 8b f4 df e6 bb
D/wpa_supplicant( 2018):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 77 dd 20 d0 bc f0 77 c4 b8 50 3d f9 02 93 33 ...
D/wpa_supplicant( 2018): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2018): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2018): Get randomness: len=32 entropy=9
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2018): WPA: Renewed SNonce - hexdump(len=32): 7c 2f 0d 13 b3 72 0d 46 bb ac bf 2c d0 9c 3e 46 91 fb 6b 1e 95 e3 e7 8f 0d 3d ac 83 9e 29 d5 56
D/wpa_supplicant( 2018): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): WPA: Nonce1 - hexdump(len=32): 7c 2f 0d 13 b3 72 0d 46 bb ac bf 2c d0 9c 3e 46 91 fb 6b 1e 95 e3 e7 8f 0d 3d ac 83 9e 29 d5 56
D/wpa_supplicant( 2018): WPA: Nonce2 - hexdump(len=32): 77 dd 20 d0 bc f0 77 c4 b8 50 3d f9 02 93 33 e0 be 41 c6 dd 6c 23 38 05 0b 8c ee 8b f4 df e6 bb
D/wpa_supplicant( 2018): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2018): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2018): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2018): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2018): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2018): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2018): WPA: Derived Key MIC - hexdump(len=16): d4 92 32 43 2f 56 76 8a 30 22 ac 6d 7d d4 35 3f
D/wpa_supplicant( 2018): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 7c 2f 0d 13 b3 72 0d 46 bb ac bf 2c d0 9c 3e ...
D/WifiStateMachine(  965): handleMessage: E msg.what=147462,
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4824 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 2018): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 77 dd 20 d0 bc f0 77 c4 b8 50 3d f9 02 93 33 ...
D/wpa_supplicant( 2018): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2018): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2018): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2018): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2018):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2018):   key_nonce - hexdump(len=32): 77 dd 20 d0 bc f0 77 c4 b8 50 3d f9 02 93 33 e0 be 41 c6 dd 6c 23 38 05 0b 8c ee 8b f4 df e6 bb
D/wpa_supplicant( 2018):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018):   key_rsc - hexdump(len=8): ae 36 00 00 00 00 00 00
D/wpa_supplicant( 2018):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2018):   key_mic - hexdump(len=16): 38 ea 79 c4 d7 d1 08 23 4b 40 05 b4 98 3e b3 4e
D/wpa_supplicant( 2018): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 77 dd 20 d0 bc f0 77 c4 b8 50 3d f9 02 93 33 ...
D/wpa_supplicant( 2018): RSN: encrypted key data - hexdump(len=56): 09 21 c3 d3 86 eb d3 a6 69 78 a9 36 70 67 35 09 e0 fd 4c 5b b2 c2 2e 47 b3 3a f1 7a ba f9 29 9a ...
D/wpa_supplicant( 2018): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2018): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2018): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2018): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 da 36 ...
D/wpa_supplicant( 2018): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2018): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2018): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2018): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2018): WPA: Derived Key MIC - hexdump(len=16): e8 55 29 9f 77 54 ec ad c1 42 e3 cc 51 f1 1e eb
D/wpa_supplicant( 2018): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2018): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb778ac54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2018):    addr=c0:ff:d4:d3:aa:48
D/HyLog   ( 4824): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4824): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4824): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2018): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2018): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2018): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2018): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2018): WPA: RSC - hexdump(len=6): ae 36 00 00 00 00
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6fad03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2018):    broadcast key
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2018): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2018): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2018): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2018): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2018): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2018): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2018): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2018): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2018): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2018): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2018): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2018): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2018): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2018): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2018): EAPOL authentication completed successfully
D/wpa_supplicant( 2018): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2018): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2018): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  965): processMsg: DisconnectedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection established
D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2018): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCMP
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=Obtainin,gIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/DhcpStateMachine(  965): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@43aac020 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-11ms what=147462 obj=android.net.wifi.StateChangeResult@439b9438 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-11ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-1ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2018): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2018): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/DownloadManager( 4824): DownloadService onCreate
,I/DownloadManager( 4824): in removeSpuriousFiles
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4824): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/wpa_supplicant( 2018): wpa_driver_nl80211_driver_cmd OK len = 0, 2
V/DownloadManager( 4824): DownloadService onStartCommand
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  965): doBoolean: SET ps 0
,V/DownloadManager( 4824): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2018): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2018): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2018): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2018): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2018): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@43097848 on behalf of 4824
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
,D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2018): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2018): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
,I/DownloadManager( 4824): in trimDatabase
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/eas_req ( 4591): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4824): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@43099768 on behalf of 4824
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43901578 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43901578 target=com.android.internal.util.StateMachine$SmHandler }
V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@4309afd8 on behalf of 4824
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  965): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  965): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  965): doBoolean: SET ps 1
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = false
,D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2018): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2018): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2018): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2018): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2018): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): DHCP successful
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
,D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  965): handleMessage: X
D/WifiP2pService(  965): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4846 uid=10052 gids={50052, 3003}
,W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  965): send additional Connectivity Action
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  596): Reading a NULL string not supported here.
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
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
W/linker  ( 4591): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/HtmlEditor( 4591): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4591): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4591): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
V/DownloadManager( 4824): DownloadService onDestroy
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  965): handleMessage: X
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/dalvikvm( 4591): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
D/HtmlEditor( 4591): register_HtmlEditor, Success
D/HtmlEditor( 4591): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4591): register_HtmlEditorTimer, Success
D/HtmlEditor( 4591): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4591): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4591): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/HtmlEditor( 4591): register_HtmlEditorFont, Success
D/HtmlEditor( 4591): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4591): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4591): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
D/HtmlEditor( 4591): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4591): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4591): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4591): JNI_OnLoad Success
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/HubEmail( 4591): JNI_OnLoad()
I/HubEmail( 4591): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4591): registerNatives()
I/HubEmail( 4591): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4591): registerNativeMethods()
I/HubEmail( 4591): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/Parcel  (  596): Reading a NULL string not supported here.
D/HyLog   ( 4846),: I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/        (  264): RouteController
,I/ActivityManager(  965): Killing 3912:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,V/LGRssiData( 4846): [loadRssi] File not exist 
,V/LGRssiData( 4846): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4846): [loadFeatureFromXml] *** start feature loading from xml
,V/        (  264): RouteController
W/BaseRuntimeLoader( 4846): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4846): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4846): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4846): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling( 4846): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4846): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4846): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  264): RouteController
D/MobileConnectivityChangeReceiver( 4846): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4846): onReceive CONNECTIVITY_CHANGE networkType=1
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  965): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4876 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4354:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
E/PhoneMonitor( 4846): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4846): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/QCNEA   (  596): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  596): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  596): |CAC| updateNetCfgInfo
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC|                   Netconfig               
V/QCNEA   (  596): |CAC| *********************************************
V/QCNEA   (  596): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  596): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  596): |CAC| 	NetConfig:         fl =21
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  596): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  596): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  596): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  596): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| net type = 1
V/QCNEA   (  596): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  596): |CAC| Received ssid= NG700
V/QCNEA   (  596): |CAC| 	ssid           =NG700
V/QCNEA   (  596): |CAC| 	DNS v4        =192.168.1.1
,V/QCNEA   (  596): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  596): |CAC| *********************************************
D/QCNEA   (  596): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  596): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  596): |CAC| dispatchNetCfg: updating:0xb8f0b8dc
,D/QCNEA   (  596): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4876): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4876): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1966): Checking schedule, now: 1450287801556 next: 1450287744722
,I/CheckinService( 1966): active receiver: enabled
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1450287711867
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4900 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  965): Killing 4516:com.android.defcontainer/u0a4 (adj 15): empty #17
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4900): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4900): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4900): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 4549:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/dalvikvm( 1545): GC_EXPLICIT freed 1256K, 29% free 17831K/24832K, paused 2ms+8ms, total 41ms
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4913 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4913): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4913): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4927 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  965): Killing 4578:com.lge.bnr/1000 (adj 15): empty #17
,D/HyLog   ( 4927): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4927): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4927): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4927): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4927): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4927): intf.getDisplayName() = lo
I/Wireless_Storage( 4927): intf.getDisplayName() = sit0
I/Wireless_Storage( 4927): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4927): intf.getDisplayName() = teql0
I/Wireless_Storage( 4927): intf.getDisplayName() = wlan0
,D/NFS     ( 4927): interface name:wlan0 name:wlan0
D/NFS     ( 4927): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4927): interface name:wlan0 name:wlan0
,D/NFS     ( 4927): addr:192.168.1.140 broadcast:192.168.1.255
,I/Wireless_Storage( 4927): CONNECT : WIFI_CONNECT
,I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4939 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4243:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4939): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4939): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43b202e8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4978 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HyLog   ( 4978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4978): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 2ms+2ms, total 26ms
,W/dalvikvm( 4978): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4978): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4978): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4978): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4978): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 4978): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4978): install
,I/MultiDex( 4978): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4978): loading existing secondary dex files
,I/MultiDex( 4978): load found 3 secondary dex files
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 19ms
,I/MultiDex( 4978): install done
,D/dalvikvm( 4978): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4978): VFY: unable to resolve instance field 61
,D/dalvikvm( 4978): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4978): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4978): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4978): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4978): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4978): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4978): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4978): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4978): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430616b0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
,D/dalvikvm( 4978): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430616b0
,D/dalvikvm( 4978): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430616b0, skipping init
,D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430616b0
D/dalvikvm( 4978): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430616b0
,V/JNIHelp ( 4978): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
V/LgDhcpStateMachineHelper(  965): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
,V/WebViewChromium( 4939): Binding Chromium to the main looper Looper (main, tid 1) {4305a320}
,I/chromium( 4939): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4939): Initializing chromium process, renderers=0
,W/chromium( 4939): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4939): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4939): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4939): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4939): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4939): Remote Branch: 
I/Adreno-EGL( 4939): Local Patches: 
I/Adreno-EGL( 4939): Reconstruct Branch: 
,D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x430616b0
,D/dalvikvm( 4978): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x430616b0
D/dalvikvm( 4978): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x430616b0
,D/dalvikvm( 4978): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x430616b0
,I/NSApplication( 4939): Starting up...
,I/ActivityManager(  965): Killing 4258:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4771): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4771): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 4978): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4771): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4737): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4737): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4771): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4771): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4771): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4771): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1545): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1545): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1966): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 4978): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4978): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4978): VFY: replacing opcode 0x6e at 0x000d
,D/WearableService( 1877): callingUid 10006, callindPid: 1877
,E/MDM     ( 1423): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4978): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4978): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4978): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1966): Restart initialization of location
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fce000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fce000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
D/wpa_supplicant( 2018): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2018): EAPOL: disable timer tick
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  270): PrepareKeyRequest: nonce=4017036103
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4978): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4327f148
D/dalvikvm( 4978): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4327f148
,D/dalvikvm( 4978): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4327f148, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  965): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings( 4978): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/WVCdm   (  270): PrepareKeyRequest: nonce=2990746302
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,I/jxcore-log( 4683): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4683): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4978): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5020): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 4978): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4978): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 75ms
,I/Adreno-EGL( 4978): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4978): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4978): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4978): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4978): Remote Branch: 
I/Adreno-EGL( 4978): Local Patches: 
I/Adreno-EGL( 4978): Reconstruct Branch: 
,I/Adreno-EGL( 4978): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4978): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4978): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4978): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4978): Remote Branch: 
I/Adreno-EGL( 4978): Local Patches: 
I/Adreno-EGL( 4978): Reconstruct Branch: 
,I/Adreno-EGL( 4978): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4978): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4978): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4978): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4978): Remote Branch: 
I/Adreno-EGL( 4978): Local Patches: 
I/Adreno-EGL( 4978): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/WifiStateMachine(  965): handleMessage: X
D/ConnectivityServiceHSM(  965): send additional Connectivity Action
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,I/TelephonyProvider( 1446): getPreferredApnId: subscription=0
,I/CheckinTask( 1966): Sending checkin request (11460 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  965): GC_EXPLICIT freed 2018K, 49% free 29640K/57464K, paused 5ms+12ms, total 167ms
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1966): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43d00f70: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1450287804111 next: 1450865200106
,I/CheckinService( 1966): active receiver: disabled
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4306e0c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4037): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4037): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4037): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4037): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4037): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4824): DownloadService onCreate
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4591): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4368): networkInfo.isConnected() = false
,I/DownloadManager( 4824): in removeSpuriousFiles
,V/DownloadManager( 4824): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4846): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4846): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430a1380 on behalf of 4824
V/DownloadManager( 4824): DownloadService onStartCommand
W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4824): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 4824): in trimDatabase
V/DownloadManager( 4824): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4913): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430a48a8 on behalf of 4824
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430a4b60 on behalf of 4824
,W/ContextImpl( 4913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4927): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4927): CONNECT : WIFI_CONNECT
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 4824): DownloadService onDestroy
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4306e0c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4824): DownloadService onCreate
,I/DownloadManager( 4824): in removeSpuriousFiles
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 4824): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430a99d8 on behalf of 4824
V/DownloadManager( 4824): DownloadService onStartCommand
,V/DownloadManager( 4824): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4824): in trimDatabase
,V/DownloadManager( 4824): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430abb88 on behalf of 4824
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430acba8 on behalf of 4824
I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = true
,D/PhoneState( 4368): setPdpRejectCasuse : false
,V/DownloadManager( 4824): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4846): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4846): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4913): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4927): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4927): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,W/ContextImpl( 4913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/GCM     ( 1545): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1545): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 1966): GC_CONCURRENT freed 1812K, 22% free 19523K/24832K, paused 1ms+3ms, total 32ms
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4306e0c8
,D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4824): DownloadService onCreate
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4591): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4824): in removeSpuriousFiles
,V/DownloadManager( 4824): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430b0ea0 on behalf of 4824
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 4824): in trimDatabase
,V/DownloadManager( 4824): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430b2898 on behalf of 4824
,V/DownloadManager( 4824): DownloadService onStartCommand
,I/LgeMiscReceiver( 4368): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4368): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4824): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4368): networkInfo.isConnected() = true
,D/PhoneState( 4368): setPdpRejectCasuse : false
,W/Settings( 4591): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4846): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4846): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@430b4a48 on behalf of 4824
D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4824): DownloadService onDestroy
D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4913): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4927): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4927): CONNECT : WIFI_CONNECT
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 4939): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4275): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4275): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  965): Killing 4609:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.464752 Y: -0.399933 Z: 9.745193 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464752 .y:-0.399933 .z:9.745193
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.455154 Y: -0.426132 Z: 9.766617 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455154 .y:-0.426132 .z:9.766617
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/SlideAside( 3757): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3757): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/administrator(  965): Handling package changes for user 0
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5138 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher( 1487): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5138): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5138): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Babel   ( 5138): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5138): MmsConfig.loadMmsSettings
I/Babel   ( 5138): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5138): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5138): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5138): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5138): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5138): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5138): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5138): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5138): MmsConfig.loadFromResources
E/Babel   ( 5138): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5138): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5138): [loadRssi] File not exist 
V/LGRssiData( 5138): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5138): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:Utils( 4037): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4037): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4037): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
V/TelephonyAutoProfiling( 5138): [getMatchedProfile] selected file : /cust/config/featureset.xml
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
V/TelephonyAutoProfiling( 5138): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5138): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4306e0c8
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2982): start selecting data
,D/SIMObserver( 2982): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
D/AppUp4:Utils( 4037): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4037): Event For Nothing, skip.
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5187 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1423): DISABLE
D/HyLog   ( 5187): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5187): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5187): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5187): BUILD Country: EU
,I/SystemConfig( 5187): BUILD Operator: OPEN
I/ActivityManager(  965): Killing 4737:com.lge.sync/1000 (adj 15): empty #17
,D/LocationProviderProxy(  965): applying state to connected service
,I/SystemConfig( 5187): systemFeature RCS result false
,D/SystemConfig( 5187): refreshRcsSupport() :false
,D/LocationProviderProxy(  965): applying state to connected service
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5204 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  965): Killing 4771:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5204): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5204): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5204): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/IcingCorporaProvider( 2652): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  965): Killing 4824:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  965): Delaying start of: ServiceRecord{43d021e8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2652): UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5138): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  965): [updateScreenState] screen on = false
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8705 usec
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.443100 Y: -0.403397 Z: 9.781525 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.443100 .y:-0.403397 .z:9.781525
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  965): hal_acquire_resources
,I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.441284 Y: -0.413788 Z: 9.783340 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441284 .y:-0.413788 .z:9.783340
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  320): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.455780 Y: -0.410416 Z: 9.781036 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455780 .y:-0.410416 .z:9.781036
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  965): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  965): proximitySensorChanged  positive = true
I/KnockOnPowerController(  965): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.460388 Y: -0.407349 Z: 9.771545 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460388 .y:-0.407349 .z:9.771545
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.448746 Y: -0.413498 Z: 9.782669 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448746 .y:-0.413498 .z:9.782669
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.450394 Y: -0.403702 Z: 9.782608 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450394 .y:-0.403702 .z:9.782608
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.457870 Y: -0.391876 Z: 9.805252 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457870 .y:-0.391876 .z:9.805252
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@456bfe08)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7de7450
D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
I/WindowManager(  965): No lock screen! windowToken=null
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/WifiStateMachine(  965): handleScreenStateChanged: true
,D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2018): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
,D/wpa_supplicant( 2018): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131158
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132097
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2018): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2018): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  965): handleMessage: X
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43b84390 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1845): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:43:41
,E/SlideAside( 3757): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3757): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1845): 2 : This is isUpdating : false
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1845): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:43:41
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1845): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1845): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1845): 2 : shouldTimeTickRegistered : false
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
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
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1156): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1156): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1156): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1156): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1156): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1156): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1156): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 401ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287821761, nextTick: 18272, mDrawingTime: 0
D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287821805, nextTick: 18227, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1845): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:43:41
,D/WeatherService( 1845): 2 : ACTION screen on
,D/WeatherService( 1845): 2 : shouldTimeTickRegistered : false
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/GsmSST  ( 1446): Emergency Service
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1446): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1446): [PhoneIntfMgr] sigLevel = 5
,D/WeatherService( 1845): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:43:41
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/PhoneApp( 1446): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,I/LGImmersionVibrator(  965): Vibrator off
D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3} (pause complete)
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/KeyguardViewManager( 1142): onScreenTurnedOff()
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/WifiStateMachine(  965): handleScreenStateChanged: false
D/UsbSettings( 2583): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
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
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
D/wpa_supplicant( 2018): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2018): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3} (stop complete)
V/UsbSettings( 2583): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2583): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
D/WifiController(  965): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
V/SRS_Proc(  270): ParamSet string: screen_state=off
,D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
D/WifiController(  965): battery changed pluggedType: 2
D/WifiController(  965): CMD_SCREEN_OFF 
D/WifiController(  965): shouldWifiStayAwake TRUE
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1156): clear
D/wpa_supplicant( 2018): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  965):    returned true
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/WifiStateMachine(  965): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{43488df8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{43b42f60 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/qdlights( 1156): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 81, B = 81
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
,D/dalvikvm(  965): GC_EXPLICIT freed 2791K, 49% free 29808K/57464K, paused 4ms+9ms, total 126ms
,I/[LGHome]EVENT( 1487): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
E/Parcel  (  596): Reading a NULL string not supported here.
,E/Parcel  (  596): Reading a NULL string not supported here.
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
D/WeatherService( 1845): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:43:42
D/WeatherService( 1845): 2 : ACTION screen off
,D/WeatherService( 1845): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:43:42
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1446): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1446): Emergency Service
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1446): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1446): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1446): Action intent recieved:android.intent.action.SCREEN_OFF
D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/NfcService( 1472): NFC-C OFF
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1225): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,I/Sensors (  320): sns_pwr.c(320):releasing wakelock
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiController(  965): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1446): getIsInUseVoLTE : false
,D/PhoneApp( 1446): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287829900020944; DSPS: 4948062; Offset: 1450287678897152292
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1545): Vacuum at: now=1450287831326 tag=VacuumService
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287840071, nextTick: 59961, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287840072, nextTick: 59960, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287849900568176; DSPS: 5603439; Offset: 1450287678897180725
,I/GoogleURLConnFactory( 1545): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1545): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1545): GC_CONCURRENT freed 1730K, 28% free 18109K/24832K, paused 6ms+8ms, total 54ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1545): No account for auth token provided
,W/Uploader( 1545):  no longer exists, so no auth token.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1545): No account for auth token provided
,W/Uploader( 1545): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  965): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287869902220251; DSPS: 6258854; Offset: 1450287678897154334
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287889903668317; DSPS: 6914261; Offset: 1450287678897168073
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287900043, nextTick: 59987, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287900047, nextTick: 59961, mDrawingTime: 8
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287909905532736; DSPS: 7569682; Offset: 1450287678897170920
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287929907214187; DSPS: 8225097; Offset: 1450287678897173904
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287949909068346; DSPS: 8880518; Offset: 1450287678897166491
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287960046, nextTick: 59965, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450287960059, nextTick: 59968, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287969910874067; DSPS: 9535937; Offset: 1450287678897171675
,D/wpa_supplicant( 2018): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Remove id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2018): wlan0: BSS: Remove id 7 BSSID 64:7c:34:b0:03:6e SSID 'UPC4688432' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2018): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 64:7c:34:b0:03:6e]
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450287989912419841; DSPS: 10191348; Offset: 1450287678897161052
,I/jxcore-log( 4683): Connected to the server!
I/jxcore-log( 4683): 
,I/chromium( 4683): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 2637): GC_CONCURRENT freed 7760K, 32% free 16985K/24832K, paused 3ms+3ms, total 59ms
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288009914710928; DSPS: 10846783; Offset: 1450287678897163321
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x43584800: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4275): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4275): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4275): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4275): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4275): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4275): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4275): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4275): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4275): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4275): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288020040, nextTick: 59985, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288020056, nextTick: 59975, mDrawingTime: 1
,I/LocationManagerService(  965): remove 43bb2fb8
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2637): GC_CONCURRENT freed 1928K, 32% free 17104K/24832K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 2637): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2637): GC_CONCURRENT freed 1765K, 30% free 17387K/24832K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 2637): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Mlt MonitorService( 2637): parseLastkmsg to dump
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288029916281961; DSPS: 11502194; Offset: 1450287678897177958
,I/jxcore-log( 4683): --- start :testFindPeers.js---
I/jxcore-log( 4683): 
,I/jxcore-log( 4683): testFindPeers created [object Object]
I/jxcore-log( 4683): 
,I/jxcore-log( 4683): serverPort is 8876
I/jxcore-log( 4683): 
,I/dalvikvm( 4683): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4683): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 4683): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4683): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4683): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 4683): Shutting down VM
,W/dalvikvm( 4683): threadid=1: thread exiting with uncaught exception (group=0x42018e48)
E/AndroidRuntime( 4683): FATAL EXCEPTION: main
E/AndroidRuntime( 4683): Process: com.test.thalitest, PID: 4683
E/AndroidRuntime( 4683): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4683): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4683): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4683): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4683): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4683): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4683): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4683): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4683): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4683): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4683): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4683): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4683): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4683): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4683): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  965):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  965): Killing 4591:com.lge.email/u0a24 (adj 15): empty #17
,V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Process ( 4683): Sending signal. PID: 4683 SIG: 9
,W/InputDispatcher(  965): channel '439064e0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  965): channel '439064e0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  965): Attempted to unregister already unregistered input channel '439064e0 com.test.thalitest/com.test.thalitest.MainActivity (server)'
I/ActivityManager(  965): Process com.test.thalitest (pid 4683) has died.
I/WindowState(  965): WIN DEATH: Window{439064e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  965): Client connection lost with reason: 4
V/ActivityManager(  965): moveHomeStack:
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{433808f8 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{435a1990 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{435a1990 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288049917166679; DSPS: 12157583; Offset: 1450287678897177666
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288069918050545; DSPS: 12812972; Offset: 1450287678897176522
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288080039, nextTick: 59976, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288080050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288089918493043; DSPS: 13468347; Offset: 1450287678897161256
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288109919401517; DSPS: 14123737; Offset: 1450287678897154203
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288129919853225; DSPS: 14779111; Offset: 1450287678897178665
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288140041, nextTick: 59966, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288140056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288149920731757; DSPS: 15434500; Offset: 1450287678897172187
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288169921624824; DSPS: 16089889; Offset: 1450287678897180244
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288189922074697; DSPS: 16745264; Offset: 1450287678897172354
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288200034, nextTick: 59982, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288200051, nextTick: 59973, mDrawingTime: 3
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288209923599567; DSPS: 17400674; Offset: 1450287678897171345
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288229924492629; DSPS: 18056063; Offset: 1450287678897179397
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288249924942713; DSPS: 18711438; Offset: 1450287678897171717
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288260025, nextTick: 59998, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288260056, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288269925399050; DSPS: 19366813; Offset: 1450287678897170291
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288289926730074; DSPS: 20022217; Offset: 1450287678897158541
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288309927194896; DSPS: 20677592; Offset: 1450287678897165600
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288320043, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288320056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288329927651338; DSPS: 21332967; Offset: 1450287678897164278
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288349928556878; DSPS: 21988357; Offset: 1450287678897154291
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288369929020576; DSPS: 22643732; Offset: 1450287678897160225
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288380051, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288380055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288389929472992; DSPS: 23299107; Offset: 1450287678897154877
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/WifiController(  965): battery changed pluggedType: 2
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1225): Disconnected process message: 10
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288409934182153; DSPS: 23954621; Offset: 1450287678897164331
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288429935056214; DSPS: 24610010; Offset: 1450287678897153382
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288440028, nextTick: 59980, mDrawingTime: 10
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288440056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288449935526036; DSPS: 25265385; Offset: 1450287678897165441
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288469935978323; DSPS: 25920760; Offset: 1450287678897159964
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288489941155050; DSPS: 26576289; Offset: 1450287678897179220
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288500035, nextTick: 59990, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288500038, nextTick: 59994, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288509941626984; DSPS: 27231665; Offset: 1450287678897162873
,D/Finsky  ( 4275): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4275): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4275): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4275): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4275): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4275): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4275): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1423): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288529942087142; DSPS: 27887040; Offset: 1450287678897165267
,D/Finsky  ( 4275): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4275): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288549942767440; DSPS: 28542422; Offset: 1450287678897174179
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288560076, nextTick: 59953, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288560077, nextTick: 59955, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288569943692826; DSPS: 29197813; Offset: 1450287678897153520
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288589944607723; DSPS: 29853202; Offset: 1450287678897183407
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288609945064192; DSPS: 30508577; Offset: 1450287678897182112
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288620048, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288620056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288629949506432; DSPS: 31164083; Offset: 1450287678897168786
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288649950421524; DSPS: 31819473; Offset: 1450287678897168351
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288669950884488; DSPS: 32474848; Offset: 1450287678897173551
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288680043, nextTick: 59968, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288680056, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288689951345048; DSPS: 33130223; Offset: 1450287678897176347
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288709952240211; DSPS: 33785613; Offset: 1450287678897155983
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288729953194044; DSPS: 34441004; Offset: 1450287678897163771
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288740040, nextTick: 59975, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288740049, nextTick: 59983, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288749953650348; DSPS: 35096379; Offset: 1450287678897162311
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288769954108505; DSPS: 35751754; Offset: 1450287678897162705
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288789955216721; DSPS: 36407150; Offset: 1450287678897172288
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288800036, nextTick: 59990, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288800051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288809955668612; DSPS: 37062525; Offset: 1450287678897166415
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288829956109146; DSPS: 37717899; Offset: 1450287678897179703
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288849957174357; DSPS: 38373294; Offset: 1450287678897176799
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288860091, nextTick: 59938, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288860097, nextTick: 59935, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288869958119019; DSPS: 39028685; Offset: 1450287678897175416
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288889959462638; DSPS: 39684090; Offset: 1450287678897145744
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288909960333540; DSPS: 40339478; Offset: 1450287678897162154
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288920046, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288920054, nextTick: 59978, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288929960809126; DSPS: 40994853; Offset: 1450287678897179976
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288949962149827; DSPS: 41650258; Offset: 1450287678897147386
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288969964495164; DSPS: 42305694; Offset: 1450287678897173387
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288980048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450288980051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450288989964493452; DSPS: 42961054; Offset: 1450287678897171675
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289009965918729; DSPS: 43616461; Offset: 1450287678897162626
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289029966353723; DSPS: 44271835; Offset: 1450287678897170374
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289040054, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289040055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289049966804127; DSPS: 44927210; Offset: 1450287678897163014
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289069968218785; DSPS: 45582617; Offset: 1450287678897143346
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289089968648755; DSPS: 46237991; Offset: 1450287678897146070
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289100050, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289100055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289109969553061; DSPS: 46893380; Offset: 1450287678897165366
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289129970928102; DSPS: 47548785; Offset: 1450287678897167116
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289149971399957; DSPS: 48204160; Offset: 1450287678897181207
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289160033, nextTick: 59979, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289160046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289169972322852; DSPS: 48859551; Offset: 1450287678897158058
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289189974237283; DSPS: 49514974; Offset: 1450287678897149881
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289209974698912; DSPS: 50170349; Offset: 1450287678897153746
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289220054, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289220055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289229975584573; DSPS: 50825738; Offset: 1450287678897154398
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,I/EventLogService( 1966): Aggregate from 1450287801591 (log), 1450287134556 (data)
,D/dalvikvm(  965): GC_EXPLICIT freed 2400K, 49% free 29859K/57464K, paused 15ms+13ms, total 222ms
,D/GCM     ( 1545): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289249976977308; DSPS: 51481143; Offset: 1450287678897173842
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289269977419571; DSPS: 52136518; Offset: 1450287678897158341
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289280046, nextTick: 59969, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289280057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289289978821683; DSPS: 52791924; Offset: 1450287678897156644
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289309980159657; DSPS: 53447327; Offset: 1450287678897182363
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289329980593823; DSPS: 54102702; Offset: 1450287678897158765
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289340040, nextTick: 59973, mDrawingTime: 9
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289340051, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289349981061276; DSPS: 54758077; Offset: 1450287678897168454
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289369982416279; DSPS: 55413481; Offset: 1450287678897180684
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289389983295284; DSPS: 56068870; Offset: 1450287678897174679
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289400048, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289400051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289409983755229; DSPS: 56724245; Offset: 1450287678897176860
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289429985167701; DSPS: 57379652; Offset: 1450287678897155006
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289449985603784; DSPS: 58035026; Offset: 1450287678897163843
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289460034, nextTick: 59994, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289460038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289469986055780; DSPS: 58690401; Offset: 1450287678897158075
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289489987514777; DSPS: 59345809; Offset: 1450287678897152229
,I/ProcessStatsService(  965): Prepared write state in 19ms
,I/ProcessStatsService(  965): Prepared write state in 23ms
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  965): Pruning old procstats: /data/system/procstats/state-2015-12-16-04-01-59.bin
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289509988411896; DSPS: 60001198; Offset: 1450287678897164338
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289520031, nextTick: 59981, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289520045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289529989777898; DSPS: 60656603; Offset: 1450287678897157049
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289549990666664; DSPS: 61311992; Offset: 1450287678897160805
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289569991131233; DSPS: 61967367; Offset: 1450287678897167610
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289580026, nextTick: 60000, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450289580049, nextTick: 59982, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450289589991584385; DSPS: 62622742; Offset: 1450287678897162999
,TIME-OUT KILL (timeout was 1800000ms)
```
