#### Test 50650278bcecc5c_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1885): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/GAV2    ( 4739): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  961): Killing 4148:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2}
,D/dalvikvm( 1885): GC_CONCURRENT freed 1504K, 22% free 19473K/24832K, paused 3ms+4ms, total 30ms
D/ChimeraCfgMgr( 1885): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1885): Module APK com.google.android.play.games already loaded
I/ConfigFetchService( 1885): fetch service done; releasing wakelock
I/ConfigFetchService( 1885): stopping self
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
D/AndroidRuntime( 4790): 
D/AndroidRuntime( 4790): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4790): CheckJNI is OFF
D/dalvikvm( 4790): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4790): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4790): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4790): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4790): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4790): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4790): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4790): failed to load memtrack module: -2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1885): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1885): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4790): Calling main entry com.android.commands.am.Am
I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4790
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (400 us)
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  961): startService SlideAside
W/ContextImpl(  961): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{431db390 stackId=1, 2 tasks}
D/UsbSettingsControl( 2629): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2629): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4790): Shutting down VM
I/SlideAside( 4122): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4790): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 4ms
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  961): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4811 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 4122): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4122): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/Icing   ( 1885): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/HyLog   ( 4811): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4811): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4811): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4811): Binding Chromium to the background looper Looper (main, tid 1) {428d9d78}
I/chromium( 4811): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4811): Initializing chromium process, renderers=0
I/Adreno-EGL( 4811): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4811): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4811): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4811): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4811): Remote Branch: 
I/Adreno-EGL( 4811): Local Patches: 
I/Adreno-EGL( 4811): Reconstruct Branch: 
W/chromium( 4811): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/dalvikvm( 4811): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4811): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4811): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4811): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4811): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4811): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4811): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4811): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4811): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4811): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4811): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4811): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4811): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4811): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4811): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4811): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4811): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4811): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4811): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4811): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/BaseRuntimeLoader( 4811): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4811): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4811): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4811): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/WifiController(  961): battery changed pluggedType: 2
D/OpenGLRenderer( 4811): Enabling debug mode 0
W/AwContents( 4811): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  961): IME STATUS OFF
W/AwContents( 4811): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  961): Displayed com.test.thalitest/.MainActivity: +462ms
I/ActivityManager( 4811): Timeline: Activity_idle id: android.os.BinderProxy@428db638 time:109736
D/JsMessageQueue( 4811): Set native->JS mode to OnlineEventsBridgeMode
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/dalvikvm( 4811): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428dfbd8
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
D/dalvikvm( 4811): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428dfbd8
D/jxcore_app_log( 4811): JniHelper::setJavaVM(0x417a3838), pthread_self() = 1637150728
D/JX-Cordova( 4811): jxcore cordova android initializing
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3} time:110025
D/ActivityManager(  961): no-history finish of ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{43302ed0 ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2629): [AUTORUN] onStop()
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4811): GC_CONCURRENT freed 2827K, 13% free 21825K/24832K, paused 2ms+1ms, total 46ms
,D/dalvikvm( 4811): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 155K, 13% free 21820K/24832K, paused 23ms, total 23ms
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 179K, 12% free 21854K/24832K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 23.654MB for 144892-byte allocation
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 253K, 13% free 21902K/24976K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 23.769MB for 217334-byte allocation
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 369K, 13% free 21976K/25192K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 23.946MB for 325996-byte allocation
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 568K, 14% free 22098K/25512K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 24.220MB for 488990-byte allocation
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 867K, 15% free 22275K/25992K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 24.625MB for 733480-byte allocation
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 1283K, 16% free 22532K/26712K, paused 22ms, total 22ms
,D/dalvikvm( 4811): GC_CONCURRENT freed 1675K, 15% free 22904K/26712K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4811): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 368K, 15% free 22862K/26712K, paused 36ms, total 36ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 26.074MB for 1650320-byte allocation
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/dalvikvm( 4811): GC_CONCURRENT freed 1700K, 18% free 23430K/28324K, paused 1ms+2ms, total 28ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 1355K, 17% free 23514K/28324K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 27.498MB for 2475476-byte allocation
,D/dalvikvm( 4811): GC_CONCURRENT freed 350K, 16% free 25880K/30744K, paused 1ms+2ms, total 43ms
,D/dalvikvm( 4811): GC_FOR_ALLOC freed 4267K, 21% free 24473K/30744K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4811): Grow heap (frag case) to 29.615MB for 3713210-byte allocation
,D/dalvikvm( 4811): GC_CONCURRENT freed 2854K, 26% free 25621K/34372K, paused 0ms+3ms, total 41ms
,W/jxcore-log( 4811): Initializing JXcore engine
,W/jxcore-log( 4811): JXcore engine is ready
,D/dalvikvm( 4811): GC_CONCURRENT freed 609K, 19% free 28065K/34372K, paused 4ms+1ms, total 32ms
,D/dalvikvm( 4811): WAIT_FOR_CONCURRENT_GC blocked 11ms
,W/jxcore-log( 4811): Starting JXcore engine
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/jxcore-log( 4811): Platform android
W/jxcore-log( 4811): 
,W/jxcore-log( 4811): Process ARCH arm
W/jxcore-log( 4811): 
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.459763 Y: -0.385757 Z: 9.778030 
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.481934 Y: -0.386871 Z: 9.778030 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.459763 .y:-0.385757 .z:9.778030
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.464813 Y: -0.384872 Z: 9.765610 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464813 .y:-0.384872 .z:9.765610
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
I/jxcore-log( 4811): JXcore Cordova bridge is ready!
I/jxcore-log( 4811): 
W/jxcore-log( 4811): JXcore engine is started
I/chromium( 4811): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4811): Toggling radios to true
I/jxcore-log( 4811): 
,D/BluetoothManagerService(  961): Message: 20
D/BluetoothManagerService(  961): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b225a0:true
,D/BluetoothAdapter( 4811): enable(): BT is already enabled..!
,D/WifiStateMachine(  961): handleMessage: E msg.what=131145
D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doBoolean: DISCONNECT
,I/jxcore-log( 4811): Radios toggled
I/jxcore-log( 4811): 
,D/BluetoothManagerService(  961): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  961): New client listening to asynchronous messages
D/WifiService(  961): setWifiEnabled: true pid=4811, uid=10304
E/WifiService(  961): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  961): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  961): disconnect pid=4811, uid=10304
,D/WifiService(  961): reconnect pid=4811, uid=10304
I/jxcore-log( 4811): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4811): 
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2023): TDLS: Tear down peers
D/wpa_supplicant( 2023): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4811): Perf Test app loaded loaded
I/jxcore-log( 4811): 
I/Choreographer( 4811): Skipped 61 frames!  The application may be doing too much work on its main thread.
,I/GAV2    ( 4739): Thread[GAThread,5,main]: No campaign data found.
D/wpa_supplicant( 2023): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2023): wlan0: Deauthentication notification
D/wpa_supplicant( 2023): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2023): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2023): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2023): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2023): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7309d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
,D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: ConnectedState
,W/Settings(  961): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  961): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131146
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiNative-wlan0(  961): doBoolean: RECONNECT
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2023): Fast associate: Old scan results
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2023): wlan0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147460
D/WifiStateMachine(  961): processMsg: DisconnectingState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection lost
D/WifiStateMachine(  961): Stopping DHCP and clearing IP
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  961): doBoolean: SET ps 1
I/chromium( 4811): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
,D/DhcpStateMachine(  961): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  961): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  961): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  961): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
D/QCNEA   (  681): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  681): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  681): |CAC| updateNetCfgInfo
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC|                   Netconfig               
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  681): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  681): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  681): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  681): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  681): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  681): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| Received bssid= 
D/QCNEA   (  681): |CAC| net type = 3
V/QCNEA   (  681): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  681): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  681): |CAC| 	ssid           =NG700
V/QCNEA   (  681): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  681): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  681): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  681): |CAC| dispatchNetCfg: updating:0xb7a798dc
,D/QCNEA   (  681): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiHS20(  961): hidePasspointNotification off =false
D/QcConnectivityService(  961): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  961): Attempting to switch to mobile
D/QcConnectivityService(  961): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  961): handleConnectivityChange: preConnState=1 connState=2
,I/chromium( 4811): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/WifiStateMachine(  961): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  961): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  961): invokeEnterMethods: DisconnectedState
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
I/ActivityManager(  961): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4874 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  271): RouteController
V/        (  271): RouteController
V/        (  271): RouteController
D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4874): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4874): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 4874): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,I/jxcore-log( 4811): check test folder
I/jxcore-log( 4811): 
V/        (  271): RouteController
V/        (  271): RouteController
,D/PCSuite ( 4874): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4874): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/jxcore-log( 4811): found test : ./testFindPeers.js
I/jxcore-log( 4811): 
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
,D/NetUtils(  961): android_net_utils_resetConnections in env=0x6187de08 clazz=0x6c900001 iface=wlan0 mask=0x3
D/QcConnectivityService(  961): resetConnections(wlan0, 3)
,I/ActivityManager(  961): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4911 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  961): Killing 4239:com.google.android.talk/u0a77 (adj 15): empty #17
,V/NativeCrypto( 1536): Read error: ssl=0x64ecd2d8: I/O error during system call, Connection timed out
,I/jxcore-log( 4811): found test : ./testSendData.js
I/jxcore-log( 4811): 
,V/NativeCrypto( 1536): SSL shutdown failed: ssl=0x64ecd2d8: I/O error during system call, Broken pipe
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4911): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4911): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4911): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GpsLocationProvider(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,D/QRemote ( 4911): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4911): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4911): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4911): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4911): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4911): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4911): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4911): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4911): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  961): Killing 4357:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
,I/chromium( 4811): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/DhcpStateMachine(  961): StoppedState
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1536): onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
,D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1156): GC_CONCURRENT freed 2888K, 11% free 25450K/28516K, paused 16ms+2ms, total 48ms
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
,D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4094): begin check event
,I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity
,I/ActivityManager(  961): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4938 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2023): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (12 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 8 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 9 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 10 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 12 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=12/32 last_scan_full=0
D/wpa_supplicant( 2023): wlan0: New scan results available
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2023): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2023): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2023): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 2023): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 2023): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[4] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[6] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50 wps
D/wpa_supplicant( 2023): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2023): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_,connect_policy 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb730b5a8  current_ssid=0x0
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2023): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2023): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2023): RSN: PMKSA cache search - network_ctx=0xb730b5a8 try_opportunistic=0
D/wpa_supplicant( 2023): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2023): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2023): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2023): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb730a590 (mode change)
D/wpa_supplicant( 2023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2023): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2023):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023):   * freq=2412
D/wpa_supplicant( 2023):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2023):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023):   * Auth Type 0
D/wpa_supplicant( 2023):   * WPA Versions 0x2
D/wpa_supplicant( 2023): nl80211: Connect request send successfully
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 a0:c5:62:7a:49:97]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 44:e9:dd:10:c0:ab]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 64:7c:34:38:27:cc]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 44:e9:dd:10:c0:ad]
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  961): handleMessage: E msg.what=147461
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  961): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2023): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Connect event
D/wpa_supplicant( 2023): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2023): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2023): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2023): wlan0: Association info event
D/wpa_supplicant( 2023): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2023): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): wlan0: freq=2412 MHz
D/wpa_supplicant( 2023): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2023): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2023): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2023): TDLS: Remove peers on association
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2023): EAPOL: enable timer tick
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  961): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState
W/WifiMonitor(  961): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  961): handleMessage: X
D/HyLog   ( 4938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4938): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4938): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 4e 89 b4 1a 5e b9 b2 14 f0 45 89 a3 cb 82 9b ...
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 4e 89 b4 1a 5e b9 b2 14 f0 45 89 a3 cb 82 9b ac a8 8d 36 cc a0 1d 87 9e 20 b2 ef b0 8e c0 9b 93
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 4e 89 b4 1a 5e b9 b2 14 f0 45 89 a3 cb 82 9b ...
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2023): Get randomness: len=32 entropy=11
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2023): WPA: Renewed SNonce - hexdump(len=32): e5 a3 b7 55 53 6d b3 ea d3 4f 78 88 bd 8f 75 dd 63 4a 07 31 0b cb 44 f7 4e ae 03 f3 e9 ac dd 26
D/wpa_supplicant( 2023): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): WPA: Nonce1 - hexdump(len=32): e5 a3 b7 55 53 6d b3 ea d3 4f 78 88 bd 8f 75 dd 63 4a 07 31 0b cb 44 f7 4e ae 03 f3 e9 ac dd 26
D/wpa_supplicant( 2023): WPA: Nonce2 - hexdump(len=32): 4e 89 b4 1a 5e b9 b2 14 f0 45 89 a3 cb 82 9b ac a8 8d 36 cc a0 1d 87 9e 20 b2 ef b0 8e c0 9b 93
D/wpa_supplicant( 2023): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2023): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 6f 94 79 e5 54 1e c9 36 0b 9c b4 bf a7 ec 13 f4
,D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 e5 a3 b7 55 53 6d b3 ea d3 4f 78 88 bd 8f 75 ...
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
,D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 4e 89 b4 1a 5e b9 b2 14 f0 45 89 a3 cb 82 9b ...
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 4e 89 b4 1a 5e b9 b2 14 f0 45 89 a3 cb 82 9b ac a8 8d 36 cc a0 1d 87 9e 20 b2 ef b0 8e c0 9b 93
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 25 43 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 83 b7 62 68 53 81 0f 59 c2 d3 a9 57 ff 4d 0e 57
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 4e 89 b4 1a 5e b9 b2 14 f0 45 89 a3 cb 82 9b ...
D/wpa_supplicant( 2023): RSN: encrypted key data - hexdump(len=56): 31 15 1c 69 40 99 29 b6 98 02 e7 fd ce 17 79 15 f9 00 ad 32 f6 04 7b 76 bc 62 62 ac c6 7f 89 57 ...
D/wpa_supplicant( 2023): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
,D/wpa_supplicant( 2023): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): ed c9 ff 4d 8c 30 1d e9 ab f7 a4 a7 25 10 7a cc
D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb730ac54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2023): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2023): WPA: RSC - hexdump(len=6): 25 43 00 00 00 00
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5903a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2023):    broadcast key
,I/wpa_supplicant( 2023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2023): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2023): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Authorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): EAPOL authentication completed successfully
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  961): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
,D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): Network connection established
,D/WifiNative-wlan0(  961): doString: STATUS
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2023): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  961):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  961): ssid=NG700
D/WifiNative-wlan0(  961): id=0
D/WifiNative-wlan0(  961): mode=station
D/WifiNative-wlan0(  961): pairwise_cipher=CCMP
D/WifiNative-wlan0(  961): group_cipher=CCMP
D/WifiNative-wlan0(  961): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  961): wpa_state=COMPLETED
D/WifiNative-wlan0(  961): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  961): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  961): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  961): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine(  961): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  961): invokeExitMethods: DisconnectedState
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/dalvikvm(  961): GC_CONCURRENT freed 1120K, 49% free 29669K/57540K, paused 6ms+12ms, total 151ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 81ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 80ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 79ms
D/WifiStateMachine(  961): moveTempStackToStateStack: i=1,j=5
,D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  961): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  961): handleMessage: X
D/DhcpStateMachine(  961): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  961): WaitBeforeStartState
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-103ms what=147462 obj=android.net.wifi.StateChangeResult@4357ab18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: ObtainingIpState
,D/WifiStateMachine(  961): ObtainingIpState{ when=-97ms what=147462 obj=android.net.wifi.StateChangeResult@44784d88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-99ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131155
D/WifiStateMachine(  961): processMsg: ObtainingIpState
,D/WifiStateMachine(  961): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
D/WifiStateMachine(  961): handleMessage: E msg.what=196612
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-8ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/DownloadManager( 4938): DownloadService onCreate
I/DownloadManager( 4938): in removeSpuriousFiles
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4718): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4938): DownloadService onStartCommand
,V/DownloadManager( 4938): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4938): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@42921170 on behalf of 4938
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@42922f38 on behalf of 4938
,I/DownloadManager( 4938): in trimDatabase
,V/DownloadManager( 4938): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@42925820 on behalf of 4938
I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4447): networkInfo.isConnected() = false
,W/linker  ( 4718): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4718): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4718): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4718): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4718): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4718): register_HtmlEditor, Success
D/HtmlEditor( 4718): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4718): register_HtmlEditorTimer, Success
,D/HtmlEditor( 4718): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4718): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4718): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4718): register_HtmlEditorFont, Success
D/HtmlEditor( 4718): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4718): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4718): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4718): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4718): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4718): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4718): JNI_OnLoad Success
I/HubEmail( 4718): JNI_OnLoad()
I/HubEmail( 4718): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4718): registerNatives()
I/HubEmail( 4718): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4718): registerNativeMethods()
,I/HubEmail( 4718): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4718): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  961): doBoolean: SET ps 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,V/DownloadManager( 4938): DownloadService onDestroy
,D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  961):    returned null
E/WifiStateMachine(  961): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  961):    returned null
I/ActivityManager(  961): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4979 uid=10052 gids={50052, 3003}
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cbf018 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  961): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  961): DHCP Start wake lock is acquired.
E/WifiStateMachine(  961): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring up wlan0
,D/WifiStateMachine(  961): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cbf018 target=com.android.internal.util.StateMachine$SmHandler }
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
,D/WifiNative-wlan0(  961): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
I/ActivityManager(  961): Killing 3975:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): DHCP successful
D/HyLog   ( 4979): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4979): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4979): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  961): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  961): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState enter
D/WifiStateMachine(  961): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  961): send additional Connectivity Action
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/WifiStateTracker(  961): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  961): 
W/WifiStateTracker(  961):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  961):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
D/WifiStateMachine(  961): handleMessage: E msg.what=135190
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
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  961): handleMessage: X
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  961): handleMessage: E msg.what=131092
D/WifiStateMachine(  961): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  961): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/QcConnectivityService(  961): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  961): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/WifiStateMachine(  961): transitionTo: destState=ConnectedState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  961): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,E/ActivityThread(  961): Failed to find provider info for com.lge.ims.provisioning
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  681): Reading a NULL string not supported here.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  961): handleConnectivityChange: preConnState=2 connState=1
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  271): RouteController
V/LGRssiData( 4979): [loadRssi] File not exist 
,V/LGRssiData( 4979): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4979): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4979): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4979): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4979): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/BaseRuntimeLoader( 4979): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4979): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4979): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4979): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  271): RouteController
,D/MobileConnectivityChangeReceiver( 4979): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4979): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  961): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5000 uid=10063 gids={50063, 3003, 1028, 1015}
,V/        (  271): RouteController
,V/        (  271): RouteController
I/ActivityManager(  961): Killing 4428:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,E/PhoneMonitor( 4979): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4979): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  271): RouteController
,V/        (  271): RouteController
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
,V/        (  271): RouteController
D/HyLog   ( 5000): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1885): Checking schedule, now: 1450461206167 next: 1450461151278
,I/CheckinService( 1885): active receiver: enabled
D/HyLog   ( 5000): I : /data/font/config/dfactpre.dat, No such file or directory (2)
V/        (  271): RouteController
,D/HyLog   ( 5000): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  681): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  681): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  681): |CAC| updateNetCfgInfo
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC|                   Netconfig               
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  681): |CAC| 	NetConfig: subtype rl =21
,V/QCNEA   (  681): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  681): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  681): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  681): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  681): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  681): |CAC| net type = 1
V/QCNEA   (  681): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  681): |CAC| Received ssid= NG700
V/QCNEA   (  681): |CAC| 	ssid           =NG700
V/QCNEA   (  681): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  681): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  681): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  681): |CAC| dispatchNetCfg: updating:0xb7a798dc
,D/QCNEA   (  681): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/CheckinService( 1885): Preparing to send checkin request
,I/EventLogService( 1885): Accumulating logs since 1450461117956
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/CheckinRequestBuilder( 1885): Checkin reason type: 8 attempt count: 1
,D/DhcpStateMachine(  961): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  961): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/ActivityManager(  961): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5031 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  961): Killing 4644:com.android.defcontainer/u0a4 (adj 15): empty #17
,E/ActivityThread( 1885): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5031): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5031): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5031): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  961): Killing 4676:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2953): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  961): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5047 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
,E/LGDMClient( 2953): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
D/LGDMClient( 2953): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2953): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2953): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 5047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5047): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5047): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  275): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 2ms+2ms, total 22ms
,D/LGDMSGCM( 5047): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5047): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,I/ActivityManager(  961): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5061 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  961): Killing 4704:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5061): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5061): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5061): intf.getDisplayName() = lo
I/Wireless_Storage( 5061): intf.getDisplayName() = sit0
I/Wireless_Storage( 5061): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5061): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5061): intf.getDisplayName() = wlan0
D/NFS     ( 5061): interface name:wlan0 name:wlan0
D/NFS     ( 5061): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5061): interface name:wlan0 name:wlan0
,D/NFS     ( 5061): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
,I/ActivityManager(  961): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5073 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  961): Killing 4287:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
,D/HyLog   ( 5073): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5073): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5073): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1885): awaiting user notification for token
D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x43273898: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GAV2    ( 5073): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  961): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5091 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5091): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5091): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5091): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5091): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5091): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5091): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5091): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5091): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5091): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5091): install
,I/MultiDex( 5091): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5091): loading existing secondary dex files
,I/MultiDex( 5091): load found 3 secondary dex files
,I/MultiDex( 5091): install done
,D/dalvikvm( 5091): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5091): VFY: unable to resolve instance field 61
,D/dalvikvm( 5091): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5091): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5091): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5091): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5091): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5091): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5091): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5091): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5091): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5091): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428df398
D/dalvikvm( 5091): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428df398
,D/dalvikvm( 5091): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428df398, skipping init
D/dalvikvm( 5091): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428df398
D/dalvikvm( 5091): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428df398
,V/JNIHelp ( 5091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5073): Binding Chromium to the main looper Looper (main, tid 1) {428d6e90}
,I/chromium( 5073): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5073): Initializing chromium process, renderers=0
,W/chromium( 5073): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5073): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5073): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5073): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5073): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5073): Remote Branch: 
I/Adreno-EGL( 5073): Local Patches: 
I/Adreno-EGL( 5073): Reconstruct Branch: 
,D/dalvikvm( 5091): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428df398
D/dalvikvm( 5091): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428df398
D/dalvikvm( 5091): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428df398
,D/dalvikvm( 5091): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428df398
,I/NSApplication( 5073): Starting up...
,I/ActivityManager(  961): Killing 4303:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4911): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4911): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 5091): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 4911): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4911): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4911): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4911): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4874): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4874): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4911): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4911): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4911): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4911): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/dalvikvm( 5091): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5091): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5091): VFY: replacing opcode 0x6e at 0x000d
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1536): Proximity feature is not enabled.
,I/dalvikvm( 5091): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5091): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5091): VFY: replacing opcode 0x6e at 0x0201
,V/GmsCoreStatsServiceLauncher( 1885): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3451): callingUid 10006, callindPid: 3451
,D/LocationInitializer( 1885): Restart initialization of location
,E/MDM     ( 1424): [66] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f3a000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f3a000
,D/wpa_supplicant( 2023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2023): EAPOL: disable timer tick
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=3940333408
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  961): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 5091): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42add888
D/dalvikvm( 5091): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42add888
,D/dalvikvm( 5091): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42add888, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  961): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=4179335909
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1536): Connected
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GCM     ( 1885): Message from null null
,E/GCM     ( 1885): Dropping message from null
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1536): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  961): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
,D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  961): handleMessage: X
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  961): send additional Connectivity Action
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  961): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  961):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  961): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/dalvikvm( 4811): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4811): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4811): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4811): Shutting down VM
,W/dalvikvm( 4811): threadid=1: thread exiting with uncaught exception (group=0x4189ee48)
E/AndroidRuntime( 4811): FATAL EXCEPTION: main
E/AndroidRuntime( 4811): Process: com.test.thalitest, PID: 4811
E/AndroidRuntime( 4811): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4811): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4811): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4811): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4811): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4811): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4811): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4811): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4811): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4811): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4811): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4811): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4811): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  961):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 5091): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm(  961): GC_FOR_ALLOC freed 2660K, 49% free 29579K/57540K, paused 76ms, total 76ms
,W/ProcessCpuTracker(  961): Skipping unknown process pid 5140
,W/ProcessCpuTracker(  961): Skipping unknown process pid 5158
,D/dalvikvm( 5091): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/DhcpStateMachine(  961): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  961): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  961): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
,V/LgDhcpStateMachineHelper(  961): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  961): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  961): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  961): RunningState
,D/dalvikvm( 5168): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 5091): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5091): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 184ms
,I/Adreno-EGL( 5091): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5091): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5091): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5091): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5091): Remote Branch: 
I/Adreno-EGL( 5091): Local Patches: 
I/Adreno-EGL( 5091): Reconstruct Branch: 
,I/Adreno-EGL( 5091): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5091): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5091): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5091): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5091): Remote Branch: 
I/Adreno-EGL( 5091): Local Patches: 
I/Adreno-EGL( 5091): Reconstruct Branch: 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5091): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5091): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5091): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5091): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5091): Remote Branch: 
I/Adreno-EGL( 5091): Local Patches: 
I/Adreno-EGL( 5091): Reconstruct Branch: 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1885): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/ActivityManager(  961): Activity pause timeout for ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
,V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{431db390 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  961): moveHomeStack:
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1821): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:53:28
,D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1821): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1821): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1821): 2 : TimeTick Receiver Register
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherAncestor( 1821): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:53:28
D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1821): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
D/WeatherService( 1821): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1821): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1821): 2 : Map key string is -2
D/lim     ( 1821): 2 : time = 18:53
I/WeatherReflect( 1821): Model Name : LG-D802
D/WeatherTheme( 1821): 2 : Different view - status_min_formatted : 51 != 53
D/WeatherTheme( 1821): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1821): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1821): 2 : Fixed theme : optimus
D/WeatherTheme( 1821): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1821): 2 : quick cover state : opened : 0
D/Weather.Utils( 1821): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1821): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1821): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/CheckinTask( 1885): Sending checkin request (11465 bytes)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 7200K, 10% free 70786K/78452K, paused 26ms, total 27ms
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 5516K, 9% free 60784K/66596K, paused 21ms, total 21ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 4799K, 9% free 61906K/67536K, paused 19ms, total 19ms
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@428dbfd0 time:119441
,D/UsbSettings( 2629): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2629): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2629): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2629): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{42fc5bf8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1} time:119500
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1885): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1885): Failed to find provider info for com.google.android.wearable.settings
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x4422c4f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1885): awaiting user notification for token
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/CheckinRequestBuilder( 1885): Classify the device as Phone.
,I/CheckinTask( 1885): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] request level :IDLE....
,I/CheckinService( 1885): Checking schedule, now: 1450461209081 next: 1451038605069
I/AppUp4:CustModeStarterReceiver( 4094): onReceive
D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4094): isOpenOperator : true
D/AppUp4:CustFacade( 4094): isPhone : true
I/LicenseContentProvider( 3056): start selecting data
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/SIMObserver( 3056): simInfo1
,I/CheckinService( 1885): active receiver: disabled
I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4094): begin check event
I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4094): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4094): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4094): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4094): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4094): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4938): DownloadService onCreate
,I/DownloadManager( 4938): in removeSpuriousFiles
,V/DownloadManager( 4938): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@4292a5d0 on behalf of 4938
,V/DownloadManager( 4938): DownloadService onStartCommand
V/DownloadManager( 4938): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/eas_req ( 4718): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4938): in trimDatabase
V/DownloadManager( 4938): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@4292d1b0 on behalf of 4938
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@4292dcd0 on behalf of 4938
,V/DownloadManager( 4938): DownloadService onDestroy
I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4447): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 4979): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4979): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4718): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5047): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 5047): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
I/LGDMClient( 2953): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/LGDMClient( 2953): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2953): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2953): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2953): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinService( 1885): Checking schedule, now: 1450461209182 next: 1451038605069
,I/CheckinService( 1885): active receiver: disabled
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4094): begin check event
,I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4938): DownloadService onCreate
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4938): in removeSpuriousFiles
V/DownloadManager( 4938): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4938): DownloadService onStartCommand
,V/DownloadManager( 4938): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@429330e0 on behalf of 4938
I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4447): networkInfo.isConnected() = true
,D/PhoneState( 4447): setPdpRejectCasuse : false
,W/Settings( 4718): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4979): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4979): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@42934970 on behalf of 4938
I/DownloadManager( 4938): in trimDatabase
,V/DownloadManager( 4938): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@42935e58 on behalf of 4938
,D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5047): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4938): DownloadService onDestroy
D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2953): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 5047): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2953): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2953): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2953): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2953): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/ThermalEngine(  293): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1489): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
,D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4094): begin check event
,I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4938): DownloadService onCreate
,D/EAS     ( 4718): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4447): networkInfo.isConnected() = true
,D/PhoneState( 4447): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4979): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4979): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5047): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE,
W/ContextImpl( 5047): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2953): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 4938): in removeSpuriousFiles
,V/DownloadManager( 4938): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@4293a0f0 on behalf of 4938
I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
I/DownloadManager( 4938): in trimDatabase
V/DownloadManager( 4938): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@4293b758 on behalf of 4938
E/LGDMClient( 2953): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
W/Settings( 4718): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2953): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2953): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2953): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4938): DownloadService onStartCommand
,V/DownloadManager( 4938): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4938): created cursor android.database.sqlite.SQLiteCursor@4293dc58 on behalf of 4938
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 4938): DownloadService onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/WifiServiceExtension(  961): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 5073): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  961): Killing 4739:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/Finsky  ( 4323): [408] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4323): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  961): Killing 4874:com.lge.sync/1000 (adj 15): empty #17
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.479141 Y: -0.387085 Z: 9.767258 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.479141 .y:-0.387085 .z:9.767258
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.458664 Y: -0.380432 Z: 9.783157 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458664 .y:-0.380432 .z:9.783157
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  961): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  961): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5308 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  961): Handling package changes for user 0
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 4122): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4122): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5308): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5308): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5308): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
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
,I/Babel   ( 5308): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5308): MmsConfig.loadMmsSettings
I/Babel   ( 5308): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5308): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5308): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5308): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5308): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5308): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5308): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5308): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5308): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5308): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5308): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5308): MmsConfig.loadFromResources
,E/Babel   ( 5308): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5308): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5308): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5308): [loadRssi] File not exist 
V/LGRssiData( 5308): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5308): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:Utils( 4094): [getPackageName] uri : package:com.google.android.gms
,D/AppUp4  ( 4094): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4094): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
V/TelephonyAutoProfiling( 5308): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5308): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5308): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4094): begin check event
D/AppUp4:Utils( 4094): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4094): Event For Nothing, skip.
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  961): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5359 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/GmsNetworkLocationProvi( 1424): DISABLE
,D/HyLog   ( 5359): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5359): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5359): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5359): BUILD Country: EU
,I/SystemConfig( 5359): BUILD Operator: OPEN
,D/dalvikvm(  961): GC_CONCURRENT freed 2189K, 47% free 30673K/56936K, paused 3ms+6ms, total 86ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 49ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 43ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 44ms
D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm(  961): WAIT_FOR_CONCURRENT_GC blocked 51ms
I/ActivityManager(  961): Killing 4911:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  961): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5375 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,I/SystemConfig( 5359): systemFeature RCS result false
,D/SystemConfig( 5359): refreshRcsSupport() :false
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Killing 4811:com.test.thalitest/u0a304 (adj 15): empty #17
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/LocationProviderProxy(  961): applying state to connected service
,D/LocationProviderProxy(  961): applying state to connected service
,D/HyLog   ( 5375): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5375): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5375): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WindowState(  961): WIN DEATH: Window{4317f400 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  961): Client connection lost with reason: 4
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{431c26a0 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
,I/InputMethodManagerService(  961): IME STATUS OFF
,W/InputMethodManagerService(  961): Got RemoteException sending setActive(false) notification to pid 4811 uid 10304
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/Binder  ( 1314): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1314): java.lang.NullPointerException
W/Binder  ( 1314): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1314): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1314): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1314): 	at dalvik.system.NativeStart.run(Native Method)
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  961): Killing 4938:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2706): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1885): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1885): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  961): Delaying start of: ServiceRecord{44297bf0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1885): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1885): GC_CONCURRENT freed 1946K, 22% free 19546K/24832K, paused 2ms+3ms, total 34ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/IcingCorporaProvider( 2706): UpdateCorporaTask done [took 215 ms] updated apps [took 215 ms] 
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  961): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
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
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5308): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  961): handleMessage: X
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.470078 Y: -0.393250 Z: 9.772049 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.470078 .y:-0.393250 .z:9.772049
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.478027 Y: -0.393219 Z: 9.779190 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.478027 .y:-0.393219 .z:9.779190
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/PowerManagerService(  961): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  961): [updateScreenState] screen on = false
D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = false
I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  961): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  961): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9390 usec
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.467880 Y: -0.380356 Z: 9.789963 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467880 .y:-0.380356 .z:9.789963
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  961): [setProximitySensorEnabled] enable = true
D/qcom_sensors_hal(  961): hal_acquire_resources
I/qcom_sensors_hal(  961): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  961): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  961): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  961): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  961): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  961): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  961): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  961): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.459702 Y: -0.398773 Z: 9.806900 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459702 .y:-0.398773 .z:9.806900
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,I/Sensors (  659): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  961): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  961): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  961): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.444702 Y: -0.385956 Z: 9.800537 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444702 .y:-0.385956 .z:9.800537
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  961): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  961): proximitySensorChanged  positive = true
I/KnockOnPowerController(  961): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.454529 Y: -0.370789 Z: 9.795975 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454529 .y:-0.370789 .z:9.795975
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.454544 Y: -0.367783 Z: 9.794296 
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454544 .y:-0.367783 .z:9.794296
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.464096 Y: -0.368530 Z: 9.777985 
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.455231 Y: -0.400696 Z: 9.775772 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.464096 .y:-0.368530 .z:9.777985
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  961): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  961): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  961): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  961): hal_process_report_ind: X: -0.467316 Y: -0.374191 Z: 9.762024 
D/qcom_sensors_hal(  961): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467316 .y:-0.374191 .z:9.762024
,D/qcom_sensors_hal(  961): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb77f0450
,D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
,V/KeyguardServiceDelegate(  961): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@433d2df8)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1142): notifyScreenOnLocked
,D/KeyguardViewMediator( 1142): handleNotifyScreenOn
D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  961): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
I/WindowManager(  961): No lock screen! windowToken=null
,E/SlideAside( 4122): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/WifiStateMachine(  961): handleScreenStateChanged: true
,D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  961): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  961): stopMonitoring
,D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131127
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=132097
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  961): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2023): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  961): handleMessage: X
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 961
V/SRS_Proc(  277): ParamSet string: screen_state=on
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{432451a8 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1821): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:53:48
,I/SlideAside( 4122): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1821): 2 : This is isUpdating : false
,D/WeatherAncestor( 1821): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:53:48
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/WeatherService( 1821): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1821): 2 : TimeTick Receiver Unregister
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  961): Excessive delay in blankDisplay() while turning screen off: 408ms
D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461228465, nextTick: 11568, mDrawingTime: 0
D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461228484, nextTick: 11548, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1821): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:53:48
,D/WeatherService( 1821): 2 : ACTION screen on
,D/WeatherService( 1821): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1821): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:53:48
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_ON
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  961): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  961): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1}
,D/qcom_sensors_hal(  961): hal_acquire_resources
D/qcom_sensors_hal(  961): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  961): hal_wait_for_response: timeout=1000
D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
V/qcom_sensors_hal(  961): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  961): hal_process_smgr_resp: 33
,D/qcom_sensors_hal(  961): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  961): hal_smgr_report_delete: Rcvd success response from request
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
,I/LGImmersionVibrator(  961): Vibrator off
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
,D/WifiStateMachine(  961): handleScreenStateChanged: false
D/WifiStateMachine(  961): handleMessage: E msg.what=131154
D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131158
D/WifiStateMachine(  961): processMsg: ConnectedState
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{43117d38 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  961): doBoolean: DRIVER SETSUSPENDMODE 1
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/KeyguardViewManager( 1142): onScreenTurnedOff()
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
,E/AudioSystem(  961): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 961
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/WifiController(  961): CMD_SCREEN_OFF 
D/WifiController(  961): shouldWifiStayAwake TRUE
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1156): clear
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
,D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  961):    returned true
,D/WifiStateMachine(  961): handleMessage: X
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
,D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
,D/WeatherService( 1821): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:53:48
,D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
,D/WeatherService( 1821): 2 : ACTION screen off
D/WeatherService( 1821): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:53:48
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : trf_based_vzw, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1474): NFC-C OFF
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): ACTION_SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  961): battery changed pluggedType: 2
D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  961): battery changed pluggedType: 2
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
,D/qdlights( 1156): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Sensors (  659): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  293): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=131155
,D/WifiStateMachine(  961): processMsg: ConnectedState
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1536): Vacuum at: now=1450461237404 tag=VacuumService
,I/GoogleURLConnFactory( 1536): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1536): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1536): No account for auth token provided
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1536): GC_EXPLICIT freed 1325K, 28% free 17888K/24832K, paused 2ms+6ms, total 44ms
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1536):  no longer exists, so no auth token.
,W/Uploader( 1536): No account for auth token provided
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461240039, nextTick: 59988, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461240054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461246154374845; DSPS: 5291480; Offset: 1450461084671220549
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1462): GC_CONCURRENT freed 1542K, 7% free 25438K/27280K, paused 2ms+2ms, total 51ms
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461266155262928; DSPS: 5946869; Offset: 1450461084671223622
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461286155705928; DSPS: 6602244; Offset: 1450461084671208858
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 6 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 fe:94:e3:11:35:3c]
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461300038, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461300054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461306156161641; DSPS: 7257618; Offset: 1450461084671237325
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461326156596931; DSPS: 7912993; Offset: 1450461084671214851
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461346157488091; DSPS: 8568382; Offset: 1450461084671221002
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461360045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461360054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461366157936997; DSPS: 9223757; Offset: 1450461084671212144
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461386158378079; DSPS: 9879131; Offset: 1450461084671225980
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 8 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 9 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 10 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 7 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:96 SSID 'UPC243894600' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 11 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 12 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 a0:c5:62:7a:49:97]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 44:e9:dd:10:c0:ab]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 06:7c:34:38:27:cc]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:96]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 64:7c:34:38:27:cc]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 44:e9:dd:10:c0:ad]
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461406159710893; DSPS: 10534535; Offset: 1450461084671216020
,D/dalvikvm( 2694): GC_CONCURRENT freed 7739K, 32% free 16914K/24832K, paused 3ms+1ms, total 39ms
,D/dalvikvm( 2694): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461420046, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461420055, nextTick: 59978, mDrawingTime: 0
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x42d33860: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/GLSActivity( 1536): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1536): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 4323): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4323): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4323): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4323): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4323): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4323): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4323): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4323): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4323): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4323): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461426160611675; DSPS: 11189924; Offset: 1450461084671231793
,I/LocationManagerService(  961): remove 435874d8
,D/LocationManagerService(  961): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  961): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  961): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2694): GC_CONCURRENT freed 1944K, 32% free 17017K/24832K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 2694): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2694): GC_FOR_ALLOC freed 1496K, 31% free 17178K/24832K, paused 20ms, total 21ms
,D/dalvikvm( 2694): GC_FOR_ALLOC freed 1240K, 31% free 17330K/24832K, paused 20ms, total 20ms
,I/Mlt MonitorService( 2694): parseLastkmsg to dump
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461446161048243; DSPS: 11845299; Offset: 1450461084671210597
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461466163296184; DSPS: 12500732; Offset: 1450461084671230755
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461480044, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461480054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461486163740500; DSPS: 13156107; Offset: 1450461084671217307
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461506164175557; DSPS: 13811481; Offset: 1450461084671225118
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461526164616943; DSPS: 14466856; Offset: 1450461084671208740
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Disconnect event
D/wpa_supplicant( 2023): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2023): wlan0: Deauthentication notification
D/wpa_supplicant( 2023): wlan0:  * reason 0
D/wpa_supplicant( 2023): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 500000 usec
,D/wpa_supplicant( 2023): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2023): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2023): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,D/WifiStateMachine(  961): handleMessage: E msg.what=147460,
D/WifiStateMachine(  961): processMsg: ConnectedState,
D/WifiStateMachine(  961): processMsg: L2ConnectedState,
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): Network connection lost,
D/WifiStateMachine(  961): Stopping DHCP and clearing IP,
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  961): doBoolean: SET ps 1
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7309d6c key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2023): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT),
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
,D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
,D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  961):    returned true
,D/DhcpStateMachine(  961): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  961): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  961): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  961): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2023): wlan0: nl80211: scan request
,D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2023): wlan0: nl80211: Scan trigger
,D/WifiHS20(  961): hidePasspointNotification off =false
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
D/QCNEA   (  681): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  681): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  681): |CAC| updateNetCfgInfo
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC|                   Netconfig               
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  681): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  681): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  681): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  681): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  681): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  681): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| Received bssid= 
D/QCNEA   (  681): |CAC| net type = 3
V/QCNEA   (  681): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  681): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  681): |CAC| 	ssid           =NG700
V/QCNEA   (  681): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  681): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  681): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  681): |CAC| dispatchNetCfg: updating:0xb7a798dc
D/QCNEA   (  681): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
D/QcConnectivityService(  961): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  961): Attempting to switch to mobile
D/QcConnectivityService(  961): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  961): handleConnectivityChange: preConnState=1 connState=2
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  961): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  961): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  961): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  961): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
,D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
D/WifiStateMachine(  961): processMsg: DisconnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
,I/ActivityManager(  961): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5799 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=131213
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiStateMachine(  961): processMsg: DefaultState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  961): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
,D/HyLog   ( 5799): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5799): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5799): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 5799): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5799): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5799): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  271): RouteController
W/NetworkManagementService(  961): route cmd failed: 
W/NetworkManagementService(  961): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  961): android_net_utils_resetConnections in env=0x6187de08 clazz=0xb7800001 iface=wlan0 mask=0x3
I/ActivityManager(  961): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5841 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  961): Killing 4718:com.lge.email/u0a24 (adj 15): empty #17
D/QcConnectivityService(  961): resetConnections(wlan0, 3)
,D/HyLog   ( 5841): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5841): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5841): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,V/NativeCrypto( 1536): Read error: ssl=0x64ecba88: I/O error during system call, Connection timed out
,V/NativeCrypto( 1536): SSL shutdown failed: ssl=0x64ecba88: I/O error during system call, Broken pipe
,D/QRemote ( 5841): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/DhcpStateMachine(  961): StoppedState
,D/QRemote ( 5841): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5841): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 5841): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5841): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5841): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5841): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5841): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5841): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  961): Killing 4979:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  961): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461540025, nextTick: 60003, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461540043, nextTick: 59989, mDrawingTime: 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2023): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 13 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 14 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): wlan0: New scan results available
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2023): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-89 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2023): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: a0:c5:62:7a:49:97 ssid='UPC503894600' wpa_ie_len=0 rsn_ie_len=20 caps=0x1111 level=-89 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: No suitable network found
I/wpa_supplicant( 2023): [LGE_PATCH]scan interval[0] = 0 sec.
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2023): wlan0: Checking for other virtual interfaces sharing same radio (phy0) in event_scan_results
D/wpa_supplicant( 2023): p2p0: Updating scan results from sibling
D/wpa_supplicant( 2023): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): p2p0: BSS: Start scan result update 1
D/wpa_supplicant( 2023): p2p0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): p2p0: BSS: Add new id 1 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 2023): p2p0: New scan results available
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added,
D/wpa_supplicant( 2023): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): p2p0: No suitable network found,
D/wpa_supplicant( 2023): [LGE_WLAN]p2p scan delay set 250ms
D/wpa_supplicant( 2023): p2p0: Short-circuit new scan request since there are no enabled networks,
,D/wpa_supplicant( 2023): p2p0: State: DISCONNECTED -> INACTIVE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2023): wlan0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: Scan trigger
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 a0:c5:62:7a:49:97]
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  961): handleMessage: E msg.what=147461
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  961): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2023): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  961): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  961): Event [IFNAME=p2p0 CTRL-EVENT-BSS-ADDED 1 a0:c5:62:7a:49:97]
,D/WifiMonitor(  961): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  961): Event [IFNAME=p2p0 CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  961): handleMessage: X
D/WifiP2pService(  961): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@441f9940 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@441f9940 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@441f9940 target=com.android.internal.util.StateMachine$SmHandler }
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
,D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4094): begin check event
,I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity
,I/ActivityManager(  961): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5873 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 5873): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5873): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5873): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 5873): DownloadService onCreate
,I/DownloadManager( 5873): in removeSpuriousFiles
,I/ActivityManager(  961): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5902 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@429218c8 on behalf of 5873
,I/DownloadManager( 5873): in trimDatabase
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5873): DownloadService onStartCommand
,V/DownloadManager( 5873): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/dalvikvm(  961): GC_EXPLICIT freed 2372K, 47% free 30643K/56936K, paused 7ms+15ms, total 175ms
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@42923f38 on behalf of 5873
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@42925e88 on behalf of 5873
D/HyLog   ( 5902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5902): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5902): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 5873): DownloadService onDestroy
I/ActivityManager(  961): Killing 5000:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/LGEmail ( 5902): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5902): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 5902): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5902): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5902): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5902): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 5902): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5902): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5902): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4447): networkInfo.isConnected() = false
,W/linker  ( 5902): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 5902): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 5902): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 5902): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/ActivityManager(  961): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5923 uid=10052 gids={50052, 3003}
I/dalvikvm( 5902): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 5902): register_HtmlEditor, Success
D/HtmlEditor( 5902): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 5902): register_HtmlEditorTimer, Success
D/HtmlEditor( 5902): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 5902): register_HtmlEditorDownloader, Success
D/HtmlEditor( 5902): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5902): register_HtmlEditorFont, Success
D/HtmlEditor( 5902): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5902): register_HtmlEditorDrawText, Success
D/HtmlEditor( 5902): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5902): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 5902): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5902): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 5902): JNI_OnLoad Success
,D/HyLog   ( 5923): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5923): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5923): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/HubEmail( 5902): JNI_OnLoad()
I/HubEmail( 5902): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 5902): registerNatives()
I/HubEmail( 5902): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5902): registerNativeMethods()
,I/HubEmail( 5902): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 5902): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+4ms, total 36ms
,I/ActivityManager(  961): Killing 5031:com.lge.drmservice/u0a66 (adj 15): empty #17
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5923): [loadRssi] File not exist 
,V/LGRssiData( 5923): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5923): [loadFeatureFromXml] *** start feature loading from xml
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+4ms, total 28ms
,W/BaseRuntimeLoader( 5923): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5923): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5923): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
W/BaseRuntimeLoader( 5923): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/TelephonyAutoProfiling( 5923): [getMatchedProfile] selected file : /cust/config/featureset.xml
D/MobileConnectivityChangeReceiver( 5923): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/TelephonyAutoProfiling( 5923): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5923): [getValue] FEATURE key : vzw_roaming_state, value : null
D/MobileConnectivityChangeReceiver( 5923): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5923): onOtaspChanged old =0, new =3
V/PhoneMonitor( 5923): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 24ms
,I/ActivityManager(  961): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5939 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  961): Killing 5047:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5939): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5939): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  961): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5952 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  961): Killing 5061:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5952): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5952): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5952): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  961): Killing 5073:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  961): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5965 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5965): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5965): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5965): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  961): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5978 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  961): Killing 5091:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5978): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5978): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 5978): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5978): intf.getDisplayName() = lo
I/Wireless_Storage( 5978): intf.getDisplayName() = sit0
I/Wireless_Storage( 5978): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5978): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5978): intf.getDisplayName() = wlan0
I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet8
I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet2
I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet3
,I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet4
I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet5
I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet6
I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet7
,I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet0
I/Wireless_Storage( 5978): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet0
I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet1
,I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet2
I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet3
I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet4
I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet5
,I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet6
I/Wireless_Storage( 5978): intf.getDisplayName() = rmnet7
,I/Wireless_Storage( 5978): CONNECT : WIFI_DISCONNECT
,I/ActivityManager(  961): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5990 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  961): Killing 5308:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5990): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5990): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5990): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 5990): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/WebViewChromium( 5990): Binding Chromium to the main looper Looper (main, tid 1) {428d9c78}
,I/chromium( 5990): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5990): Initializing chromium process, renderers=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/chromium( 5990): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5990): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5990): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5990): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5990): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5990): Remote Branch: 
I/Adreno-EGL( 5990): Local Patches: 
I/Adreno-EGL( 5990): Reconstruct Branch: 
,I/NSApplication( 5990): Starting up...
,I/ActivityManager(  961): Killing 5359:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,I/iu.Environment( 1885): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/iu.UploadsManager( 1885): num queued entries: 0
,I/iu.UploadsManager( 1885): num updated entries: 0
,I/iu.SyncManager( 1885): NEXT; no task
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461546165238789; DSPS: 15122236; Offset: 1450461084671220235
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2023): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 15 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 2023): wlan0: New scan results available
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[2] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2023): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2023): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb730b5a8  current_ssid=0x0
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
,D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01,
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00,
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
,D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2023): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2023): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 2023): wlan0: Cancelling scan request,
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2023): wlan0: Automatic auth_alg selection: 0x1,
D/wpa_supplicant( 2023): RSN: PMKSA cache search - network_ctx=0xb730b5a8 try_opportunistic=0
,D/wpa_supplicant( 2023): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2023): RSN: No PMKSA cache entry found
,D/wpa_supplicant( 2023): wlan0: RSN: using IEEE 802.11i/D9.0
,D/wpa_supplicant( 2023): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2,
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE,
,D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using KEY_MGMT WPA-PSK
,D/wpa_supplicant( 2023): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing,
D/wpa_supplicant( 2023): wlan0: State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb730a590 (mode change),
D/wpa_supplicant( 2023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb730a590,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590,
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0c,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590,
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb730a590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2023): nl80211: Connect (ifindex=23)
,D/wpa_supplicant( 2023):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2023):   * freq=2412
D/wpa_supplicant( 2023):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2023):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023):   * Auth Type 0
,D/wpa_supplicant( 2023):   * WPA Versions 0x2
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 06:7c:34:12:7f:81],
D/WifiStateMachine(  961): handleMessage: E msg.what=147461
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt,
,D/WifiStateMachine(  961): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  961): doString: BSS RANGE=0- MASK=0x21987
D/WifiMonitor(  961): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  961): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2023): nl80211: Connect request send successfully
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2023): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event,
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
,D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
,D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Connect event
D/wpa_supplicant( 2023): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2023): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2023): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2023): wlan0: Association info event
D/wpa_supplicant( 2023): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2023): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): wlan0: freq=2412 MHz
D/wpa_supplicant( 2023): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2023): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
,D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
,D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
I/wpa_supplicant( 2023): wlan0: Associated with c0:ff:d4:d3:aa:48,
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): scard is not null..,
,D/wpa_supplicant( 2023): wlan0: WPA: Association event - clear replay counter
,D/wpa_supplicant( 2023): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2023): TDLS: Remove peers on association
,D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
,D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=1,
,D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state CONNECTING,
,D/wpa_supplicant( 2023): EAPOL: enable timer tick
,D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE,
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec,
,D/wpa_supplicant( 2023): wlan0: Cancelling scan request,
,D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event,
,D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  961): handleMessage: E msg.what=147462
,D/WifiStateMachine(  961): processMsg: DisconnectedState,
D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  961): processMsg: ConnectModeState,
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiMonitor(  961): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48],
,W/WifiMonitor(  961): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2023): EAPOL: startWhen --> 0
D/wpa_supplicant( 2023): EAPOL: disable timer tick
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2023): EAPOL: enable timer tick
D/wpa_supplicant( 2023): EAPOL: txStart
,D/wpa_supplicant( 2023): WPA: drop TX EAPOL in non-IEEE 802.1X mode (type=1 len=0)
,I/GAV2    ( 5990): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 02 2b 3d e1 c5 22 e1 c9 71 ae 3d b3 61 e4 2f e1 ...
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 2b 3d e1 c5 22 e1 c9 71 ae 3d b3 61 e4 2f e1 df b0 fc 67 9f 67 f2 54 17 99 63 08 85 5e 82 ce ff
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 02 2b 3d e1 c5 22 e1 c9 71 ae 3d b3 61 e4 2f e1 ...
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2023): Get randomness: len=32 entropy=9
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  961): handleMessage: E msg.what=147462
,D/WifiStateMachine(  961): processMsg: DisconnectedState
,D/WifiStateMachine(  961): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
,D/wpa_supplicant( 2023): WPA: Renewed SNonce - hexdump(len=32): da 0d 10 77 8a f3 06 38 bf 4e 7c 82 eb 6e 12 ce 18 0d 4f b1 97 bf ba 1c 78 18 76 f4 4b 1d b5 4f
,D/wpa_supplicant( 2023): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2023): WPA: Nonce1 - hexdump(len=32): da 0d 10 77 8a f3 06 38 bf 4e 7c 82 eb 6e 12 ce 18 0d 4f b1 97 bf ba 1c 78 18 76 f4 4b 1d b5 4f
,D/wpa_supplicant( 2023): WPA: Nonce2 - hexdump(len=32): 2b 3d e1 c5 22 e1 c9 71 ae 3d b3 61 e4 2f e1 df b0 fc 67 9f 67 f2 54 17 99 63 08 85 5e 82 ce ff
,D/wpa_supplicant( 2023): WPA: PMK - hexdump(len=32): [REMOVED]
,D/wpa_supplicant( 2023): WPA: PTK - hexdump(len=48): [REMOVED],
,D/wpa_supplicant( 2023): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2023): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 02,
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 2/4,
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED],
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 6b b8 5e 13 3b 6a ab 4c f1 ab 3f d1 61 8c 7b 79,
,D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 02 da 0d 10 77 8a f3 06 38 bf 4e 7c 82 eb 6e 12 ...
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  961): NetTransition Wakelock for ConnectedState released by timeout
,D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 04 2b 3d e1 c5 22 e1 c9 71 ae 3d b3 61 e4 2f e1 ...
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 04
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 2b 3d e1 c5 22 e1 c9 71 ae 3d b3 61 e4 2f e1 df b0 fc 67 9f 67 f2 54 17 99 63 08 85 5e 82 ce ff
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 82 44 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 59 19 ea e6 c9 1f be ef 03 e9 0e f5 6c 3a 8a b4
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 04 2b 3d e1 c5 22 e1 c9 71 ae 3d b3 61 e4 2f e1 ...
D/wpa_supplicant( 2023): RSN: encrypted key data - hexdump(len=56): f2 9c 02 80 6f b4 34 99 d0 3e 85 40 ea f9 00 5c f7 26 f1 2d 85 9d 21 e4 6f f4 7f d6 fa 73 2e 33 ...
D/wpa_supplicant( 2023): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 1e 1b ...
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 65 c6 a6 ad cc 2a b9 17 e4 cb 87 2e 22 36 18 eb
,D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...,
,D/wpa_supplicant( 2023): wlan0: WPA: Installing PTK to the driver,
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb730ac54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED],
D/wpa_supplicant( 2023): WPA: Group Key - hexdump(len=16): [REMOVED],
,D/wpa_supplicant( 2023): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
,D/wpa_supplicant( 2023): WPA: RSC - hexdump(len=6): 82 44 00 00 00 00,
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5903a key_idx=1 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 2023):    broadcast key,
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700],
I/wpa_supplicant( 2023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
,D/wpa_supplicant( 2023): wlan0: Cancelling authentication timeout,
D/wpa_supplicant( 2023): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 2023): wpa_supplicant_set_state, isWPS : 0,
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 2023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE,
D/wpa_supplicant( 2023): EAPOL authentication completed successfully
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event,
,D/WifiStateMachine(  961): handleMessage: E msg.what=147462
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): handleMessage: X
,D/WifiMonitor(  961): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  961): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: DisconnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
,D/WifiStateMachine(  961): Network connection established
,D/WifiNative-wlan0(  961): doString: STATUS
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2023): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  961):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  961): ssid=NG700
D/WifiNative-wlan0(  961): id=0
D/WifiNative-wlan0(  961): mode=station
D/WifiNative-wlan0(  961): pairwise_cipher=CCMP
D/WifiNative-wlan0(  961): group_cipher=CCMP
D/WifiNative-wlan0(  961): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  961): wpa_state=COMPLETED
D/WifiNative-wlan0(  961): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  961): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  961): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  961): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  961): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/WifiStateMachine(  961): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  961): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  961): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  961): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  961): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  961): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  961): WaitBeforeStartState
,D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
,D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-37ms what=147462 obj=android.net.wifi.StateChangeResult@4332fe70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=147462
,D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-38ms what=147462 obj=android.net.wifi.StateChangeResult@4330a928 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): handleMessage: X
,D/WifiStateMachine(  961): handleMessage: E msg.what=147459
D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-39ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): handleMessage: X
D/WifiStateMachine(  961): handleMessage: E msg.what=196612
,D/WifiStateMachine(  961): processMsg: ObtainingIpState
D/WifiStateMachine(  961): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/QRemote ( 5841): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5841): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  961):    returned true
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  961): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doBoolean: SET ps 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  961):    returned null
,E/WifiStateMachine(  961): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  961): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  961):    returned null
,D/DhcpStateMachine(  961): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  961): DHCP Start wake lock is acquired.
,E/WifiStateMachine(  961): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cbf018 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  961): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42cbf018 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up wlan0
D/WifiStateMachine(  961): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
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
D/WifiStateMachine(  961): ObtainingIpState{ when=-6ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  961): processMsg: L2ConnectedState
D/WifiStateMachine(  961): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  961): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  961):    returned true
D/WifiNative-wlan0(  961): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  961):    returned true
,D/WifiNative-wlan0(  961): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  961): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  961): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  961):    returned true
,D/WifiStateMachine(  961): DHCP successful
,D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  961): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: ObtainingIpState
,D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  961): invokeEnterMethods: VerifyingLinkState
,D/WifiStateMachine(  961): VerifyingLinkState enter
,D/WifiStateMachine(  961): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  961): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  961): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  961): 
W/WifiStateTracker(  961):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  961):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
,E/Parcel  (  681): Reading a NULL string not supported here.
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  961): handleMessage: X
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  961): handleMessage: E msg.what=135190
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/WifiStateMachine(  961): processMsg: VerifyingLinkState
D/WifiStateMachine(  961): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  961): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiStateMachine(  961): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
,D/WifiStateMachine(  961): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): CaptivePortalCheckState enter
,D/WifiStateMachine(  961): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  961): handleMessage: X
D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,D/WifiStateMachine(  961): handleMessage: E msg.what=131092
D/WifiStateMachine(  961): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  961): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  961): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): handleInetConditionChange: no active default network - ignore
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  681): Reading a NULL string not supported here.
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  961): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  961): transitionTo: destState=ConnectedState
D/WifiStateMachine(  961): handleMessage: new destination call exit/enter
D/WifiStateMachine(  961): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  961): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  961): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  961): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
,D/WifiStateMachine(  961): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  961): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  961): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  681): Reading a NULL string not supported here.
E/Parcel  (  681): Reading a NULL string not supported here.
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/Parcel  (  681): Reading a NULL string not supported here.
W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  961): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QRemote ( 5841): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/ActivityThread(  961): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  961): handleConnectivityChange: preConnState=2 connState=1
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/QRemote ( 5841): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/        (  271): RouteController
,D/QRemote ( 5841): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5841): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5799): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,V/        (  271): RouteController
,D/PCSuite ( 5799): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 5841): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5841): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 5841): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5841): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/DhcpStateMachine(  961): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  961): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,D/QCNEA   (  681): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  681): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  681): |CAC| updateNetCfgInfo
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC|                   Netconfig               
V/QCNEA   (  681): |CAC| *********************************************
V/QCNEA   (  681): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  681): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  681): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  681): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  681): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  681): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  681): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  681): |CAC| net type = 1
V/QCNEA   (  681): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  681): |CAC| Received ssid= NG700
V/QCNEA   (  681): |CAC| 	ssid           =NG700
V/QCNEA   (  681): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  681): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  681): |CAC| *********************************************
D/QCNEA   (  681): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  681): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  681): |CAC| dispatchNetCfg: updating:0xb7a798dc
,D/QCNEA   (  681): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinService( 1885): Checking schedule, now: 1450461553245 next: 1450461239069
,I/CheckinService( 1885): active receiver: enabled
,I/CheckinService( 1885): Preparing to send checkin request
,I/EventLogService( 1885): Accumulating logs since 1450461206215
,I/CheckinRequestBuilder( 1885): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1885): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/CheckinRequestBuilder( 1885): awaiting user notification for token
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x4357ddf0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  961): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6096 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6096): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6096): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6096): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6096): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6096): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 6096): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6096): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6096): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6096): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6096): install
,I/MultiDex( 6096): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6096): loading existing secondary dex files
,I/MultiDex( 6096): load found 3 secondary dex files
,I/MultiDex( 6096): install done
,D/dalvikvm( 6096): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 6096): VFY: unable to resolve instance field 61
,D/dalvikvm( 6096): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 6096): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6096): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6096): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 6096): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6096): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6096): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6096): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6096): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6096): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e2608
,D/dalvikvm( 6096): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e2608
,D/dalvikvm( 6096): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e2608, skipping init
,D/dalvikvm( 6096): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428e2608
D/dalvikvm( 6096): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428e2608
,V/JNIHelp ( 6096): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 6096): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428e2608
,D/dalvikvm( 6096): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428e2608
D/dalvikvm( 6096): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428e2608
,D/dalvikvm( 6096): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428e2608
,I/ProviderInstaller( 6096): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1536): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1885): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3451): callingUid 10006, callindPid: 3451
,E/MDM     ( 1424): [67] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1885): Restart initialization of location
,I/dalvikvm( 6096): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6096): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6096): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6096): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 6096): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6096): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f3a000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f3a000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=747420477
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6096): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42abcbe8
D/dalvikvm( 6096): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42abcbe8
,D/dalvikvm( 6096): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42abcbe8, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  961): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  961): handleMessage: E msg.what=131212
D/WifiStateMachine(  961): processMsg: ConnectedState
,D/WifiStateMachine(  961): processMsg: L2ConnectedState
,D/WifiStateMachine(  961): processMsg: ConnectModeState
D/WifiStateMachine(  961): processMsg: DriverStartedState
D/WifiStateMachine(  961): processMsg: DriverStartedStateExt
D/WifiStateMachine(  961): processMsg: SupplicantStartedState
,D/WifiStateMachine(  961): processMsg: DefaultState
,D/WifiStateMachine(  961): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  961): handleMessage: X
D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  961): send additional Connectivity Action
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/GpsLocationProvider(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  961): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/QcConnectivityService(  961): handleConnectivityChange:1 is conntected
D/LocSvc_java(  961): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  961): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  961): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  961):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  961): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  961): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=270831843
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,W/Settings( 6096): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 6096): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6130): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 6096): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6096): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 74ms
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6096): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6096): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6096): Remote Branch: 
I/Adreno-EGL( 6096): Local Patches: 
I/Adreno-EGL( 6096): Reconstruct Branch: 
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6096): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6096): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6096): Remote Branch: 
I/Adreno-EGL( 6096): Local Patches: 
I/Adreno-EGL( 6096): Reconstruct Branch: 
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6096): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6096): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6096): Remote Branch: 
I/Adreno-EGL( 6096): Local Patches: 
I/Adreno-EGL( 6096): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1885): Classify the device as Phone.
,V/NativeCrypto( 1885): SSL shutdown failed: ssl=0x6cd401b8: I/O error during system call, Connection timed out
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/NativeCrypto( 1885): SSL shutdown failed: ssl=0x6cd38990: I/O error during system call, Connection timed out
,I/CheckinTask( 1885): Sending checkin request (11459 bytes)
,D/DhcpStateMachine(  961): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  961): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  961): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  961): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  961): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  961): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  961): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  961): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  961): RunningState
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
,D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
,D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4094): begin check event
,I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4094): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4094): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4094): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4094): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4094): handleAsyncCustNotification do not startCustService
,D/EAS     ( 5902): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5873): DownloadService onCreate
,D/EAS     ( 5902): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5902): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4447): networkInfo.isConnected() = false
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/MobileConnectivityChangeReceiver( 5923): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5923): onReceive CONNECTIVITY_CHANGE networkType=1
,I/DownloadManager( 5873): in removeSpuriousFiles
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@4292c200 on behalf of 5873
,I/DownloadManager( 5873): in trimDatabase
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@4292d7d0 on behalf of 5873
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 5902): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5873): DownloadService onStartCommand
V/DownloadManager( 5873): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@4292fda8 on behalf of 5873
D/LGDMSGCM( 5965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2953): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 5965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5978): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5978): CONNECT : WIFI_CONNECT
,V/DownloadManager( 5873): DownloadService onDestroy
,E/LGDMClient( 2953): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2953): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2953): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2953): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/iu.Environment( 1885): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1885): num queued entries: 0
,I/iu.UploadsManager( 1885): num updated entries: 0
,I/iu.SyncManager( 1885): NEXT; no task
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
I/CheckinRequestBuilder( 1885): Checkin reason type: 8 attempt count: 1
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4094): begin check event
,I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity, noConnectivity : false, but skip! 
E/ActivityThread( 1885): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm(  961): GC_EXPLICIT freed 2056K, 47% free 30557K/56936K, paused 5ms+12ms, total 169ms
,V/DownloadManager( 5873): DownloadService onCreate
,I/DownloadManager( 5873): in removeSpuriousFiles
D/EAS     ( 5902): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5902): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@42934110 on behalf of 5873
,I/DownloadManager( 5873): in trimDatabase
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4447): networkInfo.isConnected() = true
,D/PhoneState( 4447): setPdpRejectCasuse : false
,V/DownloadManager( 5873): DownloadService onStartCommand
,W/Settings( 5902): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@42935f80 on behalf of 5873
,D/MobileConnectivityChangeReceiver( 5923): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 5873): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 5923): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@42937c78 on behalf of 5873
,D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 5873): DownloadService onDestroy
,D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2953): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 5965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5978): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5978): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2953): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2953): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2953): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2953): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/GCM     ( 1536): Connected
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1536): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x43fade28: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm( 1536): GC_CONCURRENT freed 1705K, 27% free 18213K/24832K, paused 3ms+25ms, total 82ms
,W/CheckinRequestBuilder( 1885): awaiting user notification for token
,I/CheckinRequestBuilder( 1885): Classify the device as Phone.
,I/CheckinTask( 1885): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/CheckinService( 1885): Checking schedule, now: 1450461556891 next: 1451038952886
I/CheckinService( 1885): active receiver: disabled
,I/CheckinService( 1885): Checking schedule, now: 1450461556933 next: 1451038952886
,I/CheckinService( 1885): active receiver: disabled
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  961): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4094): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
,D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4094): begin check event
,I/AppUp4:CustModeStarterReceiver( 4094): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 5902): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 5873): DownloadService onCreate
,D/EAS     ( 5902): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4447): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4447): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4447): networkInfo.isConnected() = true
,D/PhoneState( 4447): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 5923): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5923): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2953): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5965): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5978): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5978): CONNECT : WIFI_CONNECT
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Settings( 5902): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 5873): in removeSpuriousFiles
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2953): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@4293bfc0 on behalf of 5873
I/LGDMClient( 2953): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 5873): in trimDatabase
V/DownloadManager( 5873): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 5873): DownloadService onStartCommand
V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@4293de30 on behalf of 5873
V/DownloadManager( 5873): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 2953): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2953): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@4293fba8 on behalf of 5873
D/LGDMClient( 2953): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2953): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 5873): DownloadService onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,V/WifiServiceExtension(  961): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  961): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/ActivityManager(  961): Killing 5375:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  961): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  961): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6255 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "smsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 4122): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4122): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
D/administrator(  961): Handling package changes for user 0
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mms"
W/ActivityManager(  961): getAssistContextExtras failed: no resumed activity
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "mmsto"
I/PackageManager(  961): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  961): getAssistContextExtras failed: no resumed activity
D/HyLog   ( 6255): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6255): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6255): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  961):   Action: "android.intent.action.SENDTO"
I/PackageManager(  961):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  961):   Scheme: "sms"
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
,I/Babel   ( 6255): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6255): MmsConfig.loadMmsSettings
I/MediaCodecList( 6255): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 6255): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
,I/MediaCodecList( 6255): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 6255): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 6255): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6255): MmsConfig.loadFromDatabase
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 6255): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6255): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6255): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6255): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 6255): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6255): MmsConfig.loadFromResources
,E/Babel   ( 6255): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6255): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 6255): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  961): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 6255): [loadRssi] File not exist 
,V/LGRssiData( 6255): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6255): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 6255): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6255): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6255): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4094): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4094): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4094): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4094): onReceive
,D/AppUp4:CustFacade( 4094): Context : android.app.ReceiverRestrictedContext@428f66c0
D/AppUp4:CustFacade( 4094): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4094): isOpenOperator : true
,D/AppUp4:CustFacade( 4094): isPhone : true
,I/LicenseContentProvider( 3056): start selecting data
,D/SIMObserver( 3056): simInfo1
,I/AppUp4:EulaManager( 4094): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4094): begin check event
D/AppUp4:Utils( 4094): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4094): Event For Nothing, skip.
,D/LocationProviderProxy(  961): applying state to connected service
,D/LocationProviderProxy(  961): applying state to connected service
,I/ActivityManager(  961): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6304 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6304): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6304): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6304): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6304): BUILD Country: EU
,I/SystemConfig( 6304): BUILD Operator: OPEN
I/ActivityManager(  961): Killing 4323:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  961): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6319 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 6304): systemFeature RCS result false
,D/SystemConfig( 6304): refreshRcsSupport() :false
I/ActivityManager(  961): Killing 5799:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6319): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6319): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6319): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  961): Killing 5841:com.lge.qremote/u0a96 (adj 15): empty #17
,I/IcingCorporaProvider( 2706): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  961): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6337 uid=10050 gids={50050, 3003, 1028, 1015}
D/dalvikvm( 3963): GC_FOR_ALLOC freed 398K, 2% free 37968K/38604K, paused 21ms, total 23ms
,D/HyLog   ( 6337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6337): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6337): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6337): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 6337): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6337): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6337): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/dalvikvm( 1885): GC_CONCURRENT freed 1941K, 22% free 19597K/24832K, paused 4ms+5ms, total 62ms
,I/dalvikvm( 6337): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6337): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6337): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6337): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6337): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6337): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6337): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6337): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6337): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6337): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/IcingCorporaProvider( 2706): UpdateCorporaTask done [took 324 ms] updated apps [took 324 ms] 
I/dalvikvm( 6337): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6337): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6337): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 6337): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6337): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6337): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6337): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6337): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6337): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 5873): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5873): created cursor android.database.sqlite.SQLiteCursor@42944d88 on behalf of 6337
,I/dalvikvm( 6337): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6337): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6337): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 6337): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6337): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6337): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6337): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6337): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6337): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1885): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1885): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 6337): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1885): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  961): Killing 5902:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6337): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6337): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6337): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6337): VFY: replacing opcode 0x62 at 0x0037
,D/dalvikvm(  961): GC_EXPLICIT freed 2113K, 47% free 30690K/56936K, paused 5ms+14ms, total 167ms
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6337): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6337): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6337): Total arena pages for JIT: 11
,I/dalvikvm( 6337): Total arena pages for JIT: 12
,I/dalvikvm( 6337): Total arena pages for JIT: 13
,I/dalvikvm( 6337): Total arena pages for JIT: 14
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461566166736495; DSPS: 15777645; Offset: 1450461084671222579
,D/CaptivePortalTracker(  961): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  961): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null,
D/libc    (  271): _dns_getaddrinfo: iptype =1
D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  961): Checking http://216.58.209.46/generate_204
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6337): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6337): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6337): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6337): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  961): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  961): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  961): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  961): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  961): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GAV4    ( 6255): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 2023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2023): EAPOL: disable timer tick
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6337): [519] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6337): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461586167467997; DSPS: 16433029; Offset: 1450461084671221660
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461600041, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461600043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461606167902052; DSPS: 17088403; Offset: 1450461084671228469
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461626168348281; DSPS: 17743778; Offset: 1450461084671216934
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461646168793181; DSPS: 18399152; Offset: 1450461084671234588
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461660042, nextTick: 59987, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461660045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461666169252697; DSPS: 19054528; Offset: 1450461084671205822
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461686169698700; DSPS: 19709902; Offset: 1450461084671224579
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461706170615428; DSPS: 20365292; Offset: 1450461084671225780
,I/EventLogService( 1885): Aggregate from 1450461553276 (log), 1450459811629 (data)
,I/ActivityManager(  961): Killing 5923:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42cc6e28 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461720049, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461720054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461726171073103; DSPS: 21020667; Offset: 1450461084671225691
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 13 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 14 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 15 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): p2p0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): p2p0: BSS: Remove id 1 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 a0:c5:62:7a:49:97]
D/WifiMonitor(  961): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 06:7c:34:12:7f:81]
D/WifiMonitor(  961): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  961): Event [IFNAME=p2p0 CTRL-EVENT-BSS-REMOVED 1 a0:c5:62:7a:49:97]
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461746171696602; DSPS: 21676048; Offset: 1450461084671208321
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461766172147749; DSPS: 22331422; Offset: 1450461084671232222
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461780043, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461780045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461786172600365; DSPS: 22986797; Offset: 1450461084671227074
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461806173041816; DSPS: 23642172; Offset: 1450461084671210762
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  961): battery changed pluggedType: 2
,W/Settings(  961): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  961): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1222): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461826174181599; DSPS: 24297569; Offset: 1450461084671221394
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461840046, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461840055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461846175142284; DSPS: 24952960; Offset: 1450461084671236034
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1536): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  961): updateLightListLocked :r=NotificationRecord(0x429bca60: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  961): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1536): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1536): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1536): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 6337): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6337): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6337): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 6337): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6337): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 6337): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6337): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 6337): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 6337): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 6337): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461866176090457; DSPS: 25608352; Offset: 1450461084671207645
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461886177427651; DSPS: 26263756; Offset: 1450461084671202066
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461900043, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461900045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461906178350663; DSPS: 26919146; Offset: 1450461084671209550
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461926178808190; DSPS: 27574521; Offset: 1450461084671209314
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461946180123698; DSPS: 28229924; Offset: 1450461084671212566
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461960045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450461960054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461966181090750; DSPS: 28885315; Offset: 1450461084671233573
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450461986183518494; DSPS: 29540755; Offset: 1450461084671219911
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462006184403791; DSPS: 30196144; Offset: 1450461084671220198
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462020040, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462020055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462026184887677; DSPS: 30851520; Offset: 1450461084671215802
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462046188278688; DSPS: 31506991; Offset: 1450461084671219362
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462066189152838; DSPS: 32162380; Offset: 1450461084671208503
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462080053, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462080054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462086190075113; DSPS: 32817770; Offset: 1450461084671215250
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462106191960142; DSPS: 33473192; Offset: 1450461084671208189
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462126193321023; DSPS: 34128596; Offset: 1450461084671226297
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462140036, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462140039, nextTick: 59993, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462146194226185; DSPS: 34783986; Offset: 1450461084671215932
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462166194681111; DSPS: 35439361; Offset: 1450461084671213094
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462186196060317; DSPS: 36094766; Offset: 1450461084671219009
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462200047, nextTick: 59976, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462200053, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462206196528642; DSPS: 36750141; Offset: 1450461084671229570
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462226197397920; DSPS: 37405530; Offset: 1450461084671213838
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462246198262432; DSPS: 38060918; Offset: 1450461084671223858
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462260042, nextTick: 59982, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462260047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462266198775440; DSPS: 38716295; Offset: 1450461084671218067
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462286199658915; DSPS: 39371684; Offset: 1450461084671216533
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462306200980874; DSPS: 40027087; Offset: 1450461084671226236
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462320045, nextTick: 59973, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462320054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462326202527805; DSPS: 40682498; Offset: 1450461084671216770
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462346202973600; DSPS: 41337872; Offset: 1450461084671235319
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462366204260465; DSPS: 41993275; Offset: 1450461084671209928
,D/dalvikvm( 2694): GC_CONCURRENT freed 2509K, 33% free 16741K/24832K, paused 3ms+6ms, total 63ms
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462380036, nextTick: 59966, mDrawingTime: 12
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462380056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462386204762295; DSPS: 42648651; Offset: 1450461084671223477
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462406205238325; DSPS: 43304027; Offset: 1450461084671211226
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462426206098935; DSPS: 43959415; Offset: 1450461084671217344
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462440031, nextTick: 59981, mDrawingTime: 11
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462440058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462446207036623; DSPS: 44614806; Offset: 1450461084671208987
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  961): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  961): Done.
,D/QcConnectivityService(  961): Setting timer for 720seconds
,D/GCM     ( 1536): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  961): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  961): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462466207507930; DSPS: 45270181; Offset: 1450461084671222530
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462486208833150; DSPS: 45925585; Offset: 1450461084671204977
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462500031, nextTick: 59991, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462500057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462506209290987; DSPS: 46580959; Offset: 1450461084671235568
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462526209731960; DSPS: 47236334; Offset: 1450461084671218777
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462546210660914; DSPS: 47891725; Offset: 1450461084671201686
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462560042, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462560045, nextTick: 59987, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462566211133210; DSPS: 48547100; Offset: 1450461084671216218
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462586212024982; DSPS: 49202489; Offset: 1450461084671222981
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462606212893502; DSPS: 49857877; Offset: 1450461084671237008
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462620044, nextTick: 59972, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462620054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462626213796255; DSPS: 50513267; Offset: 1450461084671224234
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462646214666312; DSPS: 51168656; Offset: 1450461084671209281
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462666215518546; DSPS: 51824044; Offset: 1450461084671207023
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462680044, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462680054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462686216505919; DSPS: 52479436; Offset: 1450461084671217834
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462706217376530; DSPS: 53134825; Offset: 1450461084671203435
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462726218232932; DSPS: 53790213; Offset: 1450461084671205345
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462740042, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462740044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462746219248561; DSPS: 54445606; Offset: 1450461084671213894
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462766219683656; DSPS: 55100980; Offset: 1450461084671221742
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462786220561916; DSPS: 55756369; Offset: 1450461084671214993
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462800039, nextTick: 59986, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462800054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462806221036423; DSPS: 56411744; Offset: 1450461084671231736
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462826222600286; DSPS: 57067155; Offset: 1450461084671239203
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462846223483556; DSPS: 57722544; Offset: 1450461084671237463
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462860038, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462860053, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462866223963630; DSPS: 58377920; Offset: 1450461084671229255
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462886224441215; DSPS: 59033296; Offset: 1450461084671218559
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462906225798243; DSPS: 59688701; Offset: 1450461084671202296
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462920079, nextTick: 59952, mDrawingTime: 2
I/ProcessStatsService(  961): Prepared write state in 50ms
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462920086, nextTick: 59944, mDrawingTime: 1
,I/ProcessStatsService(  961): Prepared write state in 30ms
,I/ProcessStatsService(  961): Pruning old procstats: /data/system/procstats/state-2015-12-18-03-54-00.bin
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462926227174551; DSPS: 60344106; Offset: 1450461084671205313
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462946228043615; DSPS: 60999494; Offset: 1450461084671219885
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462966228979363; DSPS: 61654884; Offset: 1450461084671240106
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462980064, nextTick: 59967, mDrawingTime: 1
D/Clock   ( 1142): Clock updated, drawingStartTime : 1450462980066, nextTick: 59967, mDrawingTime: 0
D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450462986229469830; DSPS: 62310261; Offset: 1450461084671211774
,D/qcom_sensors_hal(  961): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  961): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  961): hal_ts_offset_is: Apps: 1450463006229911102; DSPS: 62965635; Offset: 1450461084671225800
,TIME-OUT KILL (timeout was 1800000ms)
```
