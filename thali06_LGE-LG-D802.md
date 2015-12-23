#### Test 543122980a88295_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/PeopleContactsSync( 1900): CP2 sync disabled
W/BaseAppContext( 1900): Using Auth Proxy for data requests.
W/BaseAppContext( 1900): Using Auth Proxy for data requests.
I/dalvikvm( 1900): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1900): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1900): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1900): Using Auth Proxy for data requests.
W/BaseAppContext( 1900): Using Auth Proxy for data requests.
W/BaseAppContext( 1900): Using Auth Proxy for data requests.
W/BaseAppContext( 1900): Using Auth Proxy for data requests.
W/GAV2    ( 4702): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  968): Killing 4029:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 1900): GC_CONCURRENT freed 1739K, 22% free 19433K/24832K, paused 2ms+7ms, total 41ms
D/dalvikvm( 1900): WAIT_FOR_CONCURRENT_GC blocked 33ms
D/dalvikvm( 1900): WAIT_FOR_CONCURRENT_GC blocked 34ms
I/ConfigFetchService( 1900): fetch service done; releasing wakelock
I/ConfigFetchService( 1900): stopping self
D/ChimeraCfgMgr( 1900): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1900): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4745): 
D/AndroidRuntime( 4745): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4745): CheckJNI is OFF
D/dalvikvm( 4745): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4745): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4745): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4745): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4745): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4745): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Icing   ( 1900): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1900): Loaded CLD2 Version V2.0 - 20141016
E/memtrack( 4745): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4745): failed to load memtrack module: -2
I/Icing   ( 1900): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4745): Calling main entry com.android.commands.am.Am
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4745
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
D/PermissionCache(  268): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (115 us)
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  968): resumeTopActivityLocked: Pausing null
V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  968): setFocusedStack: mFocusedStack=ActivityStack{431296a8 stackId=1, 2 tasks}
I/ActivityManager(  968): startService SlideAside
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/UsbSettingsControl( 2587): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2587): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4745): Shutting down VM
D/dalvikvm( 4745): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/SlideAside( 3793): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Restarting ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4759 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3793): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3793): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4759): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4759): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4759): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4759): Binding Chromium to the background looper Looper (main, tid 1) {4287c500}
I/chromium( 4759): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4759): Initializing chromium process, renderers=0
W/chromium( 4759): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4759): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4759): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4759): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4759): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4759): Remote Branch: 
I/Adreno-EGL( 4759): Local Patches: 
I/Adreno-EGL( 4759): Reconstruct Branch: 
I/dalvikvm( 4759): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4759): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4759): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4759): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4759): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4759): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4759): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4759): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4759): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4759): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4759): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4759): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4759): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4759): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4759): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4759): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4759): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4759): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4759): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4759): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4759): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4759): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4759): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4759): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4759): Enabling debug mode 0
,W/AwContents( 4759): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  968): IME STATUS OFF
W/AwContents( 4759): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +361ms
,I/ActivityManager( 4759): Timeline: Activity_idle id: android.os.BinderProxy@4287dbe0 time:110685
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/JsMessageQueue( 4759): Set native->JS mode to OnlineEventsBridgeMode
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  968): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,D/dalvikvm( 4759): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42884940
,D/dalvikvm( 4759): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42884940
,D/jxcore_app_log( 4759): JniHelper::setJavaVM(0x41749838), pthread_self() = 1632311912
,D/JX-Cordova( 4759): jxcore cordova android initializing
,I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3} time:111085
D/ActivityManager(  968): no-history finish of ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  968): Finishing activity token=Token{43246bd0 ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
,V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,D/UsbSettings( 2587): [AUTORUN] onStop()
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/dalvikvm( 4759): GC_CONCURRENT freed 2777K, 12% free 21876K/24832K, paused 2ms+1ms, total 44ms
D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 226K, 12% free 21859K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 189K, 12% free 21885K/24832K, paused 35ms, total 37ms
,I/dalvikvm-heap( 4759): Grow heap (frag case) to 23.683MB for 144892-byte allocation
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 254K, 13% free 21933K/24976K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4759): Grow heap (frag case) to 23.799MB for 217334-byte allocation
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 371K, 13% free 22007K/25192K, paused 36ms, total 36ms
,I/dalvikvm-heap( 4759): Grow heap (frag case) to 23.976MB for 325996-byte allocation
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 571K, 14% free 22129K/25512K, paused 34ms, total 34ms
,I/dalvikvm-heap( 4759): Grow heap (frag case) to 24.250MB for 488990-byte allocation
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 870K, 15% free 22306K/25992K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4759): Grow heap (frag case) to 24.656MB for 733480-byte allocation
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 1290K, 16% free 22563K/26712K, paused 24ms, total 24ms
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.448029 Y: -0.396439 Z: 9.779907 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.448029 .y:-0.396439 .z:9.779907
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/dalvikvm( 4759): GC_CONCURRENT freed 1676K, 15% free 22935K/26712K, paused 2ms+3ms, total 35ms
,D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 10ms
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.452332 Y: -0.396927 Z: 9.769424 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452332 .y:-0.396927 .z:9.769424
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 378K, 15% free 22892K/26712K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4759): Grow heap (frag case) to 26.103MB for 1650320-byte allocation
,D/dalvikvm( 4759): GC_CONCURRENT freed 1762K, 18% free 23477K/28324K, paused 2ms+2ms, total 41ms
D/dalvikvm( 4759): GC_FOR_ALLOC freed 1312K, 17% free 23538K/28324K, paused 26ms, total 26ms
I/dalvikvm-heap( 4759): Grow heap (frag case) to 27.520MB for 2475476-byte allocation
D/dalvikvm( 4759): GC_CONCURRENT freed 1973K, 22% free 24231K/30744K, paused 1ms+2ms, total 47ms
D/dalvikvm( 4759): GC_CONCURRENT freed 2344K, 21% free 24475K/30744K, paused 2ms+8ms, total 65ms
D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 47ms
D/dalvikvm( 4759): GC_FOR_ALLOC freed 568K, 22% free 24271K/30744K, paused 24ms, total 24ms
I/dalvikvm-heap( 4759): Grow heap (frag case) to 29.416MB for 3713210-byte allocation
,D/dalvikvm( 4759): GC_CONCURRENT freed 221K, 19% free 27907K/34372K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 4759): GC_FOR_ALLOC freed 3028K, 26% free 25468K/34372K, paused 35ms, total 35ms
,W/jxcore-log( 4759): Initializing JXcore engine
,W/jxcore-log( 4759): JXcore engine is ready
,D/dalvikvm( 4759): GC_CONCURRENT freed 359K, 19% free 28109K/34372K, paused 1ms+1ms, total 24ms
,D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4759): WAIT_FOR_CONCURRENT_GC blocked 4ms
,W/jxcore-log( 4759): Starting JXcore engine
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,W/jxcore-log( 4759): Platform android
W/jxcore-log( 4759): 
,W/jxcore-log( 4759): Process ARCH arm
W/jxcore-log( 4759): 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/jxcore-log( 4759): JXcore Cordova bridge is ready!
I/jxcore-log( 4759): 
,W/jxcore-log( 4759): JXcore engine is started
,I/chromium( 4759): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4759): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4759): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/GAV2    ( 4702): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/jxcore-log( 4759): Toggling radios to true
I/jxcore-log( 4759): 
,D/BluetoothManagerService(  968): Message: 20
,D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43792968:true
,D/BluetoothAdapter( 4759): enable(): BT is already enabled..!
D/WifiService(  968): New client listening to asynchronous messages
,D/WifiStateMachine(  968): handleMessage: E msg.what=131145
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doBoolean: DISCONNECT
,I/jxcore-log( 4759): Radios toggled
I/jxcore-log( 4759): 
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2037): wlan0: Cancelling scan request
D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2037): TDLS: Tear down peers
,D/wpa_supplicant( 2037): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4759): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4759): 
D/wpa_supplicant( 2037): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 2037): wlan0: Deauthentication notification
D/wpa_supplicant( 2037): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2037): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2037): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiService(  968): setWifiEnabled: true pid=4759, uid=10304
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  968): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  968): disconnect pid=4759, uid=10304
D/WifiService(  968): reconnect pid=4759, uid=10304
D/wpa_supplicant( 2037): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2037): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2037): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2037): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb809ad6c key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: ,Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2037): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,I/jxcore-log( 4759): Perf Test app loaded loaded
I/jxcore-log( 4759): 
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  968): invokeExitMethods: ConnectedState
W/Settings(  968): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131146
D/WifiStateMachine(  968): processMsg: DisconnectingState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiNative-wlan0(  968): doBoolean: RECONNECT
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2037): Fast associate: Old scan results
D/wpa_supplicant( 2037): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2037): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2037): wlan0: nl80211: scan request
D/wpa_supplicant( 2037): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
I/chromium( 4759): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Choreographer( 4759): Skipped 70 frames!  The application may be doing too much work on its main thread.
D/wpa_supplicant( 2037): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147460
D/WifiStateMachine(  968): processMsg: DisconnectingState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): Network connection lost
D/WifiStateMachine(  968): Stopping DHCP and clearing IP
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  968):    returned true
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4759): check test folder
I/jxcore-log( 4759): 
I/jxcore-log( 4759): found test : ./testFindPeers.js
I/jxcore-log( 4759): 
D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiStateMachine(  968): addressRemoved: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
D/QCNEA   (  406): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  406): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  406): |CAC| updateNetCfgInfo
V/QCNEA   (  406): |CAC| *********************************************
V/QCNEA   (  406): |CAC|                   Netconfig               
V/QCNEA   (  406): |CAC| *********************************************
V/QCNEA   (  406): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  406): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  406): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  406): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  406): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  406): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  406): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  406): |CAC| *********************************************
D/QCNEA   (  406): |CAC| Received bssid= 
D/QCNEA   (  406): |CAC| net type = 3
V/QCNEA   (  406): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  406): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  406): |CAC| 	ssid           =NG700
V/QCNEA   (  406): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  406): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  406): |CAC| *********************************************
D/QCNEA   (  406): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  406): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  406): |CAC| dispatchNetCfg: updating:0xb85e98dc
,D/QCNEA   (  406): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,D/WifiStateMachine(  968): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
D/WifiHS20(  968): hidePasspointNotification off =false
D/QcConnectivityService(  968): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
,I/jxcore-log( 4759): found test : ./testSendData.js
I/jxcore-log( 4759): 
D/QcConnectivityService(  968): Attempting to switch to mobile
D/QcConnectivityService(  968): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  968): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131213
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): handleMessage: X
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4810 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  264): RouteController
D/HyLog   ( 4810): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4810): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4810): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
V/        (  264): RouteController
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4759): found test : ./testSendData2.js
I/jxcore-log( 4759): 
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
W/NetworkManagementService(  968): route cmd failed: 
W/NetworkManagementService(  968): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  968): '
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  968): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  968): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  968): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  968): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  968): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  968): android_net_utils_resetConnections in env=0x629a9810 clazz=0x6c400001 iface=wlan0 mask=0x3
,I/PCSuite ( 4810): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  968): resetConnections(wlan0, 3)
,V/NativeCrypto( 1538): Read error: ssl=0x63a08c70: I/O error during system call, Connection timed out
,V/NativeCrypto( 1538): SSL shutdown failed: ssl=0x63a08c70: I/O error during system call, Broken pipe
,D/PCSuite ( 4810): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4810): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4846 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  968): Killing 4228:com.google.android.talk/u0a77 (adj 15): empty #17
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,I/ConfigService( 1538): onDestroy
D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4846): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GpsLocationProvider(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4846): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4846): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4846): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 4846): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4846): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4846): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4846): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  968): Killing 4353:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  968): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: DisconnectedState
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): handleMessage: X
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2037): nl80211: Event message available
D/wpa_supplicant( 2037): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2037): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2037): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2037): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 2037): nl80211: Survey data missing
D/wpa_supplicant( 2037): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 4 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Add new id 5 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 2037): wlan0: New scan results available
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2037): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2037): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2037): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2037): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2037): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 2037): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2037): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56
D/wpa_supplicant( 2037): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2037): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2037): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2037): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2037): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2037): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb809c5a8  current_ssid=0x0
D/wpa_supplicant( 2037): scard is not null..
D/wpa_supplicant( 2037): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2037,): wpa_supplicant_check_mdm_ac_policy policy: 0
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
,D/wpa_supplicant( 2037): RSN: PMKSA cache search - network_ctx=0xb809c5a8 try_opportunistic=0,
,D/wpa_supplicant( 2037): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2037): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2037): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2037): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2037): wlan0: WPA: clearing AP WPA IE,
D/wpa_supplicant( 2037): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): wlan0: WPA: using GTK CCMP,
D/wpa_supplicant( 2037): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2037): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2037): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2037): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 2037): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2037): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2037): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2037): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2037): nl80211: Unsubscribe mgmt frames handle 0xb809b590 (mode change)
D/wpa_supplicant( 2037): nl80211: Subscribe to mgmt frames with non-AP handle 0xb809b590
,D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590,
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2037): nl80211: Register frame type=0xd0 nl_handle=0xb809b590
D/wpa_supplicant( 2037): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2037): nl80211: Connect (ifindex=23),
D/wpa_supplicant( 2037):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037):   * freq=2412
D/wpa_supplicant( 2037):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2037):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037):   * Auth Type 0
D/wpa_supplicant( 2037):   * WPA Versions 0x2
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48]
D/wpa_supplicant( 2037): nl80211: Connect request send successfully,
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2037): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2037): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2037): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 a0:c5:62:7a:49:97]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 fe:94:e3:11:35:3c]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 10:9a:dd:8e:22:d9],
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  968): handleMessage: E msg.what=147461
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiNative-wlan0(  968): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
,D/wpa_supplicant( 2037): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
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
D/wpa_supplicant( 2037): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
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
,D/wpa_supplicant( 2037): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2037): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2037): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2037): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  968): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 26 4b fc 70 4f af b5 91 8a 8a 2d a2 ee 60 28 ...
D/wpa_supplicant( 2037): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): 26 4b fc 70 4f af b5 91 8a 8a 2d a2 ee 60 28 c0 7c a7 58 91 c3 3b a7 53 98 b8 e3 ee 9b da e2 ea
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 26 4b fc 70 4f af b5 91 8a 8a 2d a2 ee 60 28 ...
D/wpa_supplicant( 2037): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2037): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2037): Get randomness: len=32 entropy=7
D/wpa_supplicant( 2037): WPA: Renewed SNonce - hexdump(len=32): dc 5f b6 44 e1 19 0a 80 a5 ab c5 24 f2 f2 bd a3 53 ea 78 7c 1c 93 c0 8b 41 e8 4c 80 48 42 6e 20
,D/wpa_supplicant( 2037): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): WPA: Nonce1 - hexdump(len=32): dc 5f b6 44 e1 19 0a 80 a5 ab c5 24 f2 f2 bd a3 53 ea 78 7c 1c 93 c0 8b 41 e8 4c 80 48 42 6e 20
D/wpa_supplicant( 2037): WPA: Nonce2 - hexdump(len=32): 26 4b fc 70 4f af b5 91 8a 8a 2d a2 ee 60 28 c0 7c a7 58 91 c3 3b a7 53 98 b8 e3 ee 9b da e2 ea
D/wpa_supplicant( 2037): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2037): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
,D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): e9 f5 b6 f2 0b 09 b5 73 2d 79 69 43 96 d5 f6 4d
D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 dc 5f b6 44 e1 19 0a 80 a5 ab c5 24 f2 f2 bd ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 2037): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 26 4b fc 70 4f af b5 91 8a 8a 2d a2 ee 60 28 ...
D/wpa_supplicant( 2037): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2037): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2037): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2037): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2037):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2037):   key_nonce - hexdump(len=32): 26 4b fc 70 4f af b5 91 8a 8a 2d a2 ee 60 28 c0 7c a7 58 91 c3 3b a7 53 98 b8 e3 ee 9b da e2 ea
D/wpa_supplicant( 2037):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_rsc - hexdump(len=8): ff 73 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2037):   key_mic - hexdump(len=16): b2 54 fb 20 5f 9f 0c 28 9d cd d0 4b 45 7f a9 47
D/wpa_supplicant( 2037): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 26 4b fc 70 4f af b5 91 8a 8a 2d a2 ee 60 28 ...
D/wpa_supplicant( 2037): RSN: encrypted key data - hexdump(len=56): e7 d0 aa 63 39 ea 6b ed ef a0 6e 47 34 d6 e6 07 81 b5 13 91 1e e1 df a4 50 92 80 4d a3 78 30 03 ...
D/wpa_supplicant( 2037): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2037): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2037): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 e5 4a ...
D/wpa_supplicant( 2037): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2037): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2037): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): WPA: Derived Key MIC - hexdump(len=16): aa d1 c4 85 96 a5 87 4c 33 b2 5a f3 80 e4 ca b7
D/wpa_supplicant( 2037): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2037): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb809bc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2037):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2037): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2037): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2037): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2037): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2037): WPA: RSC - hexdump(len=6): ff 73 00 00 00 00
D/wpa_supplicant( 2037): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2003a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2037):    broadcast key
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
,D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
,D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): Network connection established
,D/WifiNative-wlan0(  968): doString: STATUS
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2037): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  968):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  968): ssid=NG700
D/WifiNative-wlan0(  968): id=0
D/WifiNative-wlan0(  968): mode=station
D/WifiNative-wlan0(  968): pairwise_cipher=CCMP
D/WifiNative-wlan0(  968): group_cipher=CCMP
D/WifiNative-wlan0(  968): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  968): wpa_state=COMPLETED
D/WifiNative-wlan0(  968): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  968): address=34:fc:ef:de:0a:e2
,I/WifiServiceExtension(  968): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  968): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=5
,D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/DhcpStateMachine(  968): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): WaitBeforeStartState
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-60ms what=147462 obj=android.net.wifi.StateChangeResult@438e4480 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
,D/WifiStateMachine(  968): handleMessage: X
I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] connect :false
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
,D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-45ms what=147462 obj=android.net.wifi.StateChangeResult@43836bf0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: ObtainingIpState
I/AppUp4:CustModeStarterReceiver( 4082): onReceive
,D/WifiStateMachine(  968): ObtainingIpState{ when=-46ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/AppUp4:CustFacade( 4082): Context : android.app.ReceiverRestrictedContext@4289c440
D/AppUp4:CustFacade( 4082): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4082): isOpenOperator : true
D/AppUp4:CustFacade( 4082): isPhone : true
,D/WifiStateMachine(  968): ObtainingIpState{ when=-6ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2037): nl80211: survey data missing!
,I/LicenseContentProvider( 3012): start selecting data
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-8ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 1
D/SIMObserver( 3012): simInfo1
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/AppUp4:EulaManager( 4082): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4082): begin check event
I/AppUp4:CustModeStarterReceiver( 4082): Event For GoodConnectivity
,I/ActivityManager(  968): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4889 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4889): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  968): doBoolean: SET ps 0
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,V/DownloadManager( 4889): DownloadService onCreate
,D/WifiNative-wlan0(  968):    returned null
D/DhcpStateMachine(  968): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  968): DHCP Start wake lock is acquired.
E/WifiStateMachine(  968): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
I/DownloadManager( 4889): in removeSpuriousFiles
,D/EAS     ( 4680): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4680): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/CommandListener(  264): Setting iface cfg
,D/WifiStateMachine(  968): addressUpdated: 192.168.1.144/24 on wlan0 flags 128 scope 0
,D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  968): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  968): handleMessage: X
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4324f600 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4324f600 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.144/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196613
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/eas_req ( 4680): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4889): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2037): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2037): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2037): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428c39b8 on behalf of 4889
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): DHCP successful
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  968): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState enter
D/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/DownloadManager( 4889): in trimDatabase
,V/DownloadManager( 4889): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/WifiStateMachine(  968): handleMessage: X
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428c6f70 on behalf of 4889
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  968): send additional Connectivity Action
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  968): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  968): 
W/WifiStateTracker(  968):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  968):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 4889): DownloadService onStartCommand
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
V/DownloadManager( 4889): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/WifiStateMachine(  968): handleMessage: E msg.what=135190
D/WifiStateMachine(  968): processMsg: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  968): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  968): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState enter
,D/WifiStateMachine(  968): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428c9510 on behalf of 4889
I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4408): networkInfo.isConnected() = false
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  968): handleMessage: E msg.what=131092
D/WifiStateMachine(  968): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  968): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/QcConnectivityService(  968): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  968): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
W/linker  ( 4680): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4680): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4680): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4680): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
I/dalvikvm( 4680): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/HtmlEditor( 4680): register_HtmlEditor, Success
D/HtmlEditor( 4680): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4680): register_HtmlEditorTimer, Success
D/HtmlEditor( 4680): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4680): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4680): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4680): register_HtmlEditorFont, Success
D/HtmlEditor( 4680): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4680): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4680): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4680): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4680): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4680): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4680): JNI_OnLoad Success
I/HubEmail( 4680): JNI_OnLoad()
I/HubEmail( 4680): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4680): registerNatives()
I/HubEmail( 4680): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4680): registerNativeMethods()
I/HubEmail( 4680): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4680): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4914 uid=10052 gids={50052, 3003}
D/WifiStateMachine(  968): transitionTo: destState=ConnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 1
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/ActivityThread(  968): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  968): handleConnectivityChange: preConnState=2 connState=1
V/DownloadManager( 4889): DownloadService onDestroy
,D/HyLog   ( 4914): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4914): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4914): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  264): RouteController
I/ActivityManager(  968): Killing 3939:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
V/LGRssiData( 4914): [loadRssi] File not exist 
,V/LGRssiData( 4914): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4914): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4914): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4914): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4914): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4914): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  264): RouteController
,V/TelephonyAutoProfiling( 4914): [getMatchedProfile] selected file : /cust/config/featureset.xml
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling( 4914): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4914): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  264): RouteController
V/        (  264): RouteController
D/MobileConnectivityChangeReceiver( 4914): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4914): onReceive CONNECTIVITY_CHANGE networkType=1
V/        (  264): RouteController
,I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4942 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  968): Killing 4466:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/QCNEA   (  406): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  406): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  406): |CAC| updateNetCfgInfo
V/QCNEA   (  406): |CAC| *********************************************
V/QCNEA   (  406): |CAC|                   Netconfig               
V/QCNEA   (  406): |CAC| *********************************************
V/QCNEA   (  406): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  406): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  406): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  406): |CAC| 	NetConfig: ip4        =192.168.1.144
V/QCNEA   (  406): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  406): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  406): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  406): |CAC| *********************************************
D/QCNEA   (  406): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  406): |CAC| net type = 1
V/QCNEA   (  406): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  406): |CAC| Received ssid= NG700
V/QCNEA   (  406): |CAC| 	ssid           =NG700
V/QCNEA   (  406): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  406): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  406): |CAC| *********************************************
D/QCNEA   (  406): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  406): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  406): |CAC| dispatchNetCfg: updating:0xb85e98dc
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QCNEA   (  406): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
E/PhoneMonitor( 4914): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4914): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4942): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1900): Checking schedule, now: 1450834051173 next: 1450833994494
,I/CheckinService( 1900): active receiver: enabled
,I/CheckinService( 1900): Preparing to send checkin request
,I/EventLogService( 1900): Accumulating logs since 1450833961183
,I/CheckinRequestBuilder( 1900): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4958 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  968): Killing 4602:com.android.defcontainer/u0a4 (adj 15): empty #17
,E/ActivityThread( 1900): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
,D/DhcpStateMachine(  968): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  968): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  968): GC_EXPLICIT freed 6703K, 49% free 29712K/57704K, paused 2ms+7ms, total 94ms
,D/HyLog   ( 4958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4958): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  968): Killing 4639:com.google.android.partnersetup/u0a9 (adj 15): empty #17
D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  968): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4980 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
,E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED,
,I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4980): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4980): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4980): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  968): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4994 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  968): Killing 4667:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4994): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4994): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4994): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  269): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
,I/NFS     ( 4994): connectivityManager.getNetworkInfo = TYPE_WIFI
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,I/Wireless_Storage( 4994): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4994): intf.getDisplayName() = lo
I/Wireless_Storage( 4994): intf.getDisplayName() = sit0
I/Wireless_Storage( 4994): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4994): intf.getDisplayName() = teql0
I/Wireless_Storage( 4994): intf.getDisplayName() = wlan0
,D/NFS     ( 4994): interface name:wlan0 name:wlan0
D/NFS     ( 4994): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4994): interface name:wlan0 name:wlan0
D/NFS     ( 4994): addr:192.168.1.144 broadcast:192.168.1.255
,I/Wireless_Storage( 4994): CONNECT : WIFI_CONNECT
,D/dalvikvm(  269): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 14ms
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5006 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  968): Killing 4277:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5006): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5006): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5006): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 5006): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x430f79c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1900): awaiting user notification for token
,I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5023 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5023): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5023): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5023): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5023): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5023): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5023): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5023): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5023): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5023): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5023): install
,I/MultiDex( 5023): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5023): loading existing secondary dex files
,I/MultiDex( 5023): load found 3 secondary dex files
,I/MultiDex( 5023): install done
,D/dalvikvm( 5023): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5023): VFY: unable to resolve instance field 61
,D/dalvikvm( 5023): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5023): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5023): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5023): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5023): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5023): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5023): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5023): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5023): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5023): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428842e0
D/dalvikvm( 5023): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428842e0
,D/dalvikvm( 5023): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428842e0, skipping init
,D/dalvikvm( 5023): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428842e0
D/dalvikvm( 5023): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428842e0
,V/JNIHelp ( 5023): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 5023): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428842e0
,D/dalvikvm( 5023): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428842e0
D/dalvikvm( 5023): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428842e0
,D/dalvikvm( 5023): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428842e0
,V/WebViewChromium( 5006): Binding Chromium to the main looper Looper (main, tid 1) {4287ccf8}
,I/chromium( 5006): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5006): Initializing chromium process, renderers=0
,W/chromium( 5006): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5006): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5006): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5006): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5006): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5006): Remote Branch: 
I/Adreno-EGL( 5006): Local Patches: 
I/Adreno-EGL( 5006): Reconstruct Branch: 
,I/ProviderInstaller( 5023): Installed default security provider GmsCore_OpenSSL
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NSApplication( 5006): Starting up...
,I/dalvikvm( 5023): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 5023): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5023): VFY: replacing opcode 0x6e at 0x000d
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  968): Killing 4292:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/dalvikvm( 5023): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5023): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5023): VFY: replacing opcode 0x6e at 0x0201
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4846): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4810): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4810): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4846): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4846): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4846): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4846): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1538): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1538): Proximity feature is not enabled.
D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d82000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1d82000
,V/GmsCoreStatsServiceLauncher( 1900): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/wpa_supplicant( 2037): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2037): EAPOL: disable timer tick
D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DhcpStateMachine(  968): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  968): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  968): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.144
V/LgDhcpStateMachineHelper(  968): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  968): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  968): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  968): RunningState
,D/WearableService( 1762): callingUid 10006, callindPid: 1762
,D/LocationInitializer( 1900): Restart initialization of location
D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,E/MDM     ( 1425): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=1831253614
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5023): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a8e1d0
D/dalvikvm( 5023): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a8e1d0
,D/dalvikvm( 5023): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a8e1d0, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  968): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,W/Settings( 5023): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=105380490
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  968): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.144/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/WifiStateMachine(  968): handleMessage: X
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  968): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  968):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  968): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,I/dalvikvm( 4759): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4759): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 4759): Shutting down VM
,W/dalvikvm( 4759): threadid=1: thread exiting with uncaught exception (group=0x41844e48)
E/AndroidRuntime( 4759): FATAL EXCEPTION: main
E/AndroidRuntime( 4759): Process: com.test.thalitest, PID: 4759
E/AndroidRuntime( 4759): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4759): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4759): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4759): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4759): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4759): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4759): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4759): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4759): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4759): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4759): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4759): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4759): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4759): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4759): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4759): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4759): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4759): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4759): 	at dalvik.system.NativeStart.main(Native Method)
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ActivityManager(  968):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 5023): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5117): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/dalvikvm( 5023): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5023): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,I/Adreno-EGL( 5023): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5023): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5023): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5023): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5023): Remote Branch: 
I/Adreno-EGL( 5023): Local Patches: 
I/Adreno-EGL( 5023): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Adreno-EGL( 5023): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5023): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5023): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5023): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5023): Remote Branch: 
I/Adreno-EGL( 5023): Local Patches: 
I/Adreno-EGL( 5023): Reconstruct Branch: 
,I/Adreno-EGL( 5023): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5023): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5023): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5023): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5023): Remote Branch: 
I/Adreno-EGL( 5023): Local Patches: 
I/Adreno-EGL( 5023): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1900): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/ActivityManager(  968): Activity pause timeout for ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f}
,V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431296a8 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  968): moveHomeStack:
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
,V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  968): resumeTopActivityLocked: Resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1490): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1490): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1490): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1816): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 2:27:33
,D/UpdateThreadPoolManager( 1816): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1816): 2 : quick cover state : opened : 0
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1816): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1816): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1816): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1816): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1816): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 2:27:33
,D/WeatherService( 1816): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1816): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1816): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1816): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1816): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1816): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1816): 2 : This is isUpdating : false
D/WeatherService( 1816): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1816): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1816): 2 : Map key string is -2
,D/lim     ( 1816): 2 : time = 02:27
I/WeatherReflect( 1816): Model Name : LG-D802
,D/WeatherTheme( 1816): 2 : Different view - status_min_formatted : 25 != 27
D/WeatherTheme( 1816): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1816): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1816): 2 : Fixed theme : optimus
,D/WeatherTheme( 1816): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1816): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1816): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 5524K, 9% free 60785K/66636K, paused 18ms, total 18ms
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 7202K, 10% free 70967K/78656K, paused 40ms, total 41ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/CheckinTask( 1900): Sending checkin request (11607 bytes)
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1490): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1490): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1490): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/dalvikvm( 1490): GC_FOR_ALLOC freed 4800K, 9% free 61906K/67576K, paused 19ms, total 19ms
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@42882040 time:120889
,D/UsbSettings( 2587): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2587): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2587): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2587): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  968): Moving to DESTROYING: ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{43246a68 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1} time:120951
V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  968): Moving to DESTROYING: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/CheckinRequestBuilder( 1900): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1900): Failed to find provider info for com.google.android.wearable.settings
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1538): GC_EXPLICIT freed 776K, 29% free 17844K/24832K, paused 2ms+6ms, total 43ms
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1900): awaiting user notification for token
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/CheckinRequestBuilder( 1900): Classify the device as Phone.
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4082): onReceive
,D/AppUp4:CustFacade( 4082): Context : android.app.ReceiverRestrictedContext@4289c440
D/AppUp4:CustFacade( 4082): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4082): isOpenOperator : true
,D/AppUp4:CustFacade( 4082): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/SIMObserver( 3012): simInfo1
I/AppUp4:EulaManager( 4082): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4082): begin check event
I/AppUp4:CustModeStarterReceiver( 4082): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4082): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/dalvikvm( 1900): GC_CONCURRENT freed 1865K, 22% free 19542K/24832K, paused 6ms+9ms, total 98ms
D/AppUp4:CustModeStarterReceiver( 4082): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4082): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4082): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4082): handleAsyncCustNotification do not startCustService
,D/dalvikvm(  968): GC_CONCURRENT freed 2192K, 47% free 30838K/57704K, paused 6ms+9ms, total 174ms
D/dalvikvm(  968): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm(  968): WAIT_FOR_CONCURRENT_GC blocked 162ms
D/dalvikvm(  968): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm(  968): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
V/DownloadManager( 4889): DownloadService onCreate
,D/Tethering(  968): MasterInitialState.processMessage what=3
,I/DownloadManager( 4889): in removeSpuriousFiles
,V/DownloadManager( 4889): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x447088f8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428cf498 on behalf of 4889
D/EAS     ( 4680): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4680): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4680): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 4889): in trimDatabase
V/DownloadManager( 4889): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428d0e90 on behalf of 4889
V/DownloadManager( 4889): DownloadService onStartCommand
V/DownloadManager( 4889): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428d3080 on behalf of 4889
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4408): networkInfo.isConnected() = false
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/MobileConnectivityChangeReceiver( 4914): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/DownloadManager( 4889): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4914): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4680): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/CheckinTask( 1900): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/LGDMSGCM( 4980): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/NFS     ( 4994): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4994): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/CheckinService( 1900): Checking schedule, now: 1450834054227 next: 1451411450218
I/CheckinService( 1900): active receiver: disabled
,E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinService( 1900): Checking schedule, now: 1450834054272 next: 1451411450218
,I/CheckinService( 1900): active receiver: disabled
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4082): onReceive
D/AppUp4:CustFacade( 4082): Context : android.app.ReceiverRestrictedContext@4289c440
D/AppUp4:CustFacade( 4082): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4082): isOpenOperator : true
,D/AppUp4:CustFacade( 4082): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 4082): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4082): begin check event
,I/AppUp4:CustModeStarterReceiver( 4082): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4889): DownloadService onCreate
,I/DownloadManager( 4889): in removeSpuriousFiles
,D/EAS     ( 4680): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4680): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4889): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428d7ae0 on behalf of 4889
,V/DownloadManager( 4889): DownloadService onStartCommand
V/DownloadManager( 4889): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 4889): in trimDatabase
,V/DownloadManager( 4889): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428da768 on behalf of 4889
,V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428da980 on behalf of 4889
I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4408): networkInfo.isConnected() = true
D/PhoneState( 4408): setPdpRejectCasuse : false
,W/Settings( 4680): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4914): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4914): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4889): DownloadService onDestroy
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4980): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/NFS     ( 4994): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4994): CONNECT : WIFI_CONNECT
,W/ContextImpl( 4980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinService( 1900): Checking schedule, now: 1450834054343 next: 1451411450218
,I/CheckinService( 1900): active receiver: disabled
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1538): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1538): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1538): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GCM     ( 1538): Connected
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/GCM     ( 1900): Message from null null
E/GCM     ( 1900): Dropping message from null
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1538): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1538): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1538): No account for auth token provided
,W/Uploader( 1538): No account for auth token provided
,W/Uploader( 1538):  no longer exists, so no auth token.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1490): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1490): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1490): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4082): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4082): onReceive
,D/AppUp4:CustFacade( 4082): Context : android.app.ReceiverRestrictedContext@4289c440
,D/AppUp4:CustFacade( 4082): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4082): isOpenOperator : true
,D/AppUp4:CustFacade( 4082): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 4082): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4082): begin check event
,I/AppUp4:CustModeStarterReceiver( 4082): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4680): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4889): DownloadService onCreate
,D/EAS     ( 4680): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4408): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4408): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4408): networkInfo.isConnected() = true
,D/PhoneState( 4408): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4914): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4914): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2882): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4980): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4994): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4994): CONNECT : WIFI_CONNECT
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2882): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/DownloadManager( 4889): in removeSpuriousFiles
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4889): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428defe8 on behalf of 4889
W/Settings( 4680): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LGDMClient( 2882): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
I/DownloadManager( 4889): in trimDatabase
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
V/DownloadManager( 4889): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4889): DownloadService onStartCommand
V/DownloadManager( 4889): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428e2208 on behalf of 4889
V/DownloadManager( 4889): created cursor android.database.sqlite.SQLiteCursor@428e26e8 on behalf of 4889
,E/LGDMClient( 2882): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,V/DownloadManager( 4889): DownloadService onDestroy
,D/LGDMClient( 2882): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2882): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2882): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  968): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 5006): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  968): Killing 4702:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4316): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4316): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.455597 Y: -0.391037 Z: 9.752548 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455597 .y:-0.391037 .z:9.752548
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.469086 Y: -0.398178 Z: 9.771332 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469086 .y:-0.398178 .z:9.771332
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,W/ProcessCpuTracker(  968): Skipping unknown process pid 5237
,W/ProcessCpuTracker(  968): Skipping unknown process pid 5239
,I/ActivityManager(  968): Killing 4810:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1490): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5242 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  968): Handling package changes for user 0
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 3793): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3793): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5242): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5242): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5242): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
I/Babel   ( 5242): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5242): MmsConfig.loadMmsSettings
I/Babel   ( 5242): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5242): MmsConfig.loadFromDatabase
I/MediaCodecList( 5242): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5242): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5242): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5242): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5242): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/BaseRuntimeLoader( 5242): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5242): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5242): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5242): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5242): MmsConfig.loadFromResources
E/Babel   ( 5242): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5242): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 5242): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5242): [loadRssi] File not exist 
,V/LGRssiData( 5242): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5242): [loadFeatureFromXml] *** start feature loading from xml
D/AppUp4:Utils( 4082): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4082): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4082): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/[LGHome]EVENT( 1490): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/AppUp4:CustModeStarterReceiver( 4082): onReceive
V/TelephonyAutoProfiling( 5242): [getMatchedProfile] selected file : /cust/config/featureset.xml
,V/TelephonyAutoProfiling( 5242): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5242): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:CustFacade( 4082): Context : android.app.ReceiverRestrictedContext@4289c440
D/AppUp4:CustFacade( 4082): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4082): isOpenOperator : true
,D/AppUp4:CustFacade( 4082): isPhone : true
,I/LicenseContentProvider( 3012): start selecting data
,V/GmsNetworkLocationProvi( 1425): DISABLE
,D/SIMObserver( 3012): simInfo1
,I/AppUp4:EulaManager( 4082): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4082): begin check event
D/AppUp4:Utils( 4082): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4082): Event For Nothing, skip.
,I/GCoreNlp( 1425): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5293 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5293): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5293): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5293): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  968): applying state to connected service
,D/LocationProviderProxy(  968): applying state to connected service
,I/SystemConfig( 5293): BUILD Country: EU
,I/SystemConfig( 5293): BUILD Operator: OPEN
I/ActivityManager(  968): Killing 4846:com.lge.qremote/u0a96 (adj 15): empty #17
I/ActivityManager(  968): Killing 4759:com.test.thalitest/u0a304 (adj 15): empty #17
,I/WindowState(  968): WIN DEATH: Window{44e567b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  968): Client connection lost with reason: 4
,I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5309 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{4338a638 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1490): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/SystemConfig( 5293): systemFeature RCS result false
,D/SystemConfig( 5293): refreshRcsSupport() :false
I/InputMethodManagerService(  968): IME STATUS OFF
,W/Binder  ( 1305): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1305): java.lang.NullPointerException
W/Binder  ( 1305): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1305): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1305): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1305): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 4759 uid 10304
,D/HyLog   ( 5309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5309): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  968): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1219): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/ActivityManager(  968): Killing 4889:android.process.media/u0a23 (adj 15): empty #17
,I/IcingCorporaProvider( 2676): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1900): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1900): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  968): Delaying start of: ServiceRecord{433c7658 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1900): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2676): UpdateCorporaTask done [took 245 ms] updated apps [took 245 ms] 
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  968): Checking http://216.58.209.46/generate_204
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/CaptivePortalTracker(  968): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  968): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  968): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  968): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV4    ( 5242): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2037): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.455826 Y: -0.392700 Z: 9.767929 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.455826 .y:-0.392700 .z:9.767929
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.456665 Y: -0.390884 Z: 9.762833 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456665 .y:-0.390884 .z:9.762833
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,I/PowerManagerService(  968): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  968): [updateScreenState] screen on = false
D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  968): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8635 usec
,D/qcom_sensors_hal(  968): hal_acquire_resources
,I/qcom_sensors_hal(  968): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  968): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  968): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  968): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  968): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  968): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  968): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.475006 Y: -0.375488 Z: 9.772964 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.475006 .y:-0.375488 .z:9.772964
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.459106 Y: -0.384354 Z: 9.769669 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459106 .y:-0.384354 .z:9.769669
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/Sensors (  360): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  968): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  968): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  968): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  968): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  968): proximitySensorChanged  positive = true
I/KnockOnPowerController(  968): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.458481 Y: -0.400742 Z: 9.758255 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458481 .y:-0.400742 .z:9.758255
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.471542 Y: -0.395554 Z: 9.763702 
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.473755 Y: -0.405533 Z: 9.764816 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.471542 .y:-0.395554 .z:9.763702
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.445557 Y: -0.415512 Z: 9.765930 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445557 .y:-0.415512 .z:9.765930
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.452164 Y: -0.385056 Z: 9.775711 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452164 .y:-0.385056 .z:9.775711
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  968): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44365550)
,D/KeyguardViewMediator( 1142): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1142): notifyScreenOnLocked
D/KeyguardViewMediator( 1142): handleNotifyScreenOn
,D/KeyguardViewManager( 1142): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  968): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,I/WindowManager(  968): No lock screen! windowToken=null
D/SurfaceFlinger(  268): Screen released, type=0 flinger=0xb8c79450
D/qdhwcomposer(  268): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.452972 Y: -0.383514 Z: 9.763123 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452972 .y:-0.383514 .z:9.763123
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  968): handleScreenStateChanged: true
,D/WifiStateMachine(  968): handleMessage: E msg.what=131154
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2037): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  968): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  968): stopMonitoring
,D/wpa_supplicant( 2037): nl80211: survey data missing!
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131127
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=132097
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  968): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2037): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2037): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  968): handleMessage: X
,E/AudioSystem(  968): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 968
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1156): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433c3d50 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/qdlights( 1156): set_light_notifications: 0,0,0,0,3
D/EmotionalLed( 1156): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1156): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1156): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3793): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1816): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 2:27:51
,I/SlideAside( 3793): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1816): 2 : This is isUpdating : false
,D/WeatherAncestor( 1816): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 2:27:51
,D/WeatherService( 1816): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1816): 2 : TimeTick Receiver Unregister
D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
D/qdlights( 1156): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1156): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1156): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 195, B = 195
,D/qdhwcomposer(  268): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  968): Excessive delay in blankDisplay() while turning screen off: 414ms
D/qdlights( 1156): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 189, B = 189
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 183, B = 183
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
D/qdlights( 1156): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834071666, nextTick: 8367, mDrawingTime: 0
,D/qdlights( 1156): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1156): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834071694, nextTick: 8339, mDrawingTime: 0
D/qdlights( 1156): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 159, B = 159
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=4
,D/WeatherService( 1816): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:27:51
,D/WeatherService( 1816): 2 : ACTION screen on
,D/WeatherService( 1816): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1816): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:27:51
D/qdlights( 1156): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 153, B = 153
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
D/qdlights( 1156): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 147, B = 147
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_ON
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qdlights( 1156): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 141, B = 141
,D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1142): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1142): notifyScreenOffLocked
,V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1490): [Launcher.java:894:onPause()]onPause
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.456741 Y: -0.389450 Z: 9.780701 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456741 .y:-0.389450 .z:9.780701
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  968): hal_acquire_resources
D/qcom_sensors_hal(  968): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  968): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=1000
D/qdlights( 1156): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1156): [Current] = 255, R = 0, G = 135, B = 135
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  968): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  968): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  968): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1156): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 129, B = 129
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/KeyguardViewMediator( 1142): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/qdlights( 1156): set_light_notifications: 2,ff007b7b,10,0,2
D/KeyguardViewMediator( 1142): handleNotifyScreenOff
D/KeyguardViewManager( 1142): onScreenTurnedOff()
,D/qdlights( 1156): [Current] = 255, R = 0, G = 123, B = 123
,I/LGImmersionVibrator(  968): Vibrator off
,D/WifiStateMachine(  968): handleScreenStateChanged: false
,I/[LGHome]EVENT( 1490): [Launcher.java:4955:onStop()]onStop
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1} (pause complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/WifiStateMachine(  968): handleMessage: E msg.what=131154
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/qdlights( 1156): set_light_notifications: 2,ff007575,10,0,2
D/WifiStateMachine(  968): processMsg: ConnectedState
D/qdlights( 1156): [Current] = 255, R = 0, G = 117, B = 117
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  968): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 968
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 2037): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2037): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{42dd7518 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  968): CMD_SCREEN_OFF 
D/WifiController(  968): shouldWifiStayAwake TRUE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1156): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 111, B = 111
,E/CliptrayService( 1156): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1156): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1156): clear
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2037): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/NativeNfcBrcmPowerMode( 1477): setPowerMode; state=2
D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): handleMessage: X
D/qdlights( 1156): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 105, B = 105
,I/[LGHome]EVENT( 1490): [Launcher.java:1567:onReceive()]Screen Off
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1156): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 99, B = 99
,D/WeatherService( 1816): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:27:51
D/WeatherService( 1816): 2 : ACTION screen off
D/WeatherService( 1816): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:27:51
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
,E/Parcel  (  406): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1156): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 93, B = 93
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1477): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/NfcService( 1477): NFC-C OFF
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_OFF
D/qdlights( 1156): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1156): [Current] = 255, R = 0, G = 87, B = 87
D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1463): [TangibleIO] LCD is off. Remove tangible if exist.
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
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
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  360): sns_pwr.c(320):releasing wakelock
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  968): GC_EXPLICIT freed 2826K, 47% free 30711K/57064K, paused 5ms+14ms, total 173ms
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,D/KeyguardViewMediator( 1142): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1142): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1142): OMADM Lock is OFF
,D/KeyguardViewMediator( 1142): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1142): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834080058, nextTick: 59974, mDrawingTime: 0
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834080060, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834089425649879; DSPS: 5273982; Offset: 1450833928476492165
,D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834109427558866; DSPS: 5929405; Offset: 1450833928476478544
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834129428866244; DSPS: 6584808; Offset: 1450833928476473666
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834140038, nextTick: 59992, mDrawingTime: 1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834140055, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834149429753779; DSPS: 7240197; Offset: 1450833928476476192
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834169431029788; DSPS: 7895599; Offset: 1450833928476470462
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834189432408185; DSPS: 8551003; Offset: 1450833928476506086
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834200052, nextTick: 59977, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834200055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834209433746062; DSPS: 9206408; Offset: 1450833928476470672
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834229434591131; DSPS: 9861795; Offset: 1450833928476491766
,D/wpa_supplicant( 2037): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 4 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2037): wlan0: BSS: Remove id 5 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2037): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 fe:94:e3:11:35:3c]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 10:9a:dd:8e:22:d9],
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834249435475889; DSPS: 10517184; Offset: 1450833928476491514
,D/dalvikvm( 2651): GC_CONCURRENT freed 7763K, 32% free 16889K/24832K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 2651): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834260039, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834260046, nextTick: 59985, mDrawingTime: 1
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x444a7d00: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm( 1538): GC_CONCURRENT freed 1759K, 27% free 18131K/24832K, paused 3ms+4ms, total 102ms
,D/dalvikvm( 1538): WAIT_FOR_CONCURRENT_GC blocked 50ms
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4316): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4316): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4316): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4316): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4316): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4316): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4316): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4316): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4316): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834269437483445; DSPS: 11172610; Offset: 1450833928476484910
,I/LocationManagerService(  968): remove 4312a6d0
,D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  968): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  968): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  968): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2651): GC_CONCURRENT freed 1723K, 31% free 17214K/24832K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 2651): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2651): GC_CONCURRENT freed 1940K, 31% free 17321K/24832K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 2651): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2651): GC_FOR_ALLOC freed 1416K, 30% free 17546K/24832K, paused 19ms, total 19ms
,I/Mlt MonitorService( 2651): parseLastkmsg to dump
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834289438404667; DSPS: 11828000; Offset: 1450833928476490605
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1463): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UsbTangibleController( 1463): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1463): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1463): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834309439718899; DSPS: 12483403; Offset: 1450833928476492581
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834320040, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834320048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834329440594585; DSPS: 13138792; Offset: 1450833928476483257
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834349441028335; DSPS: 13794166; Offset: 1450833928476489761,
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834369441472353; DSPS: 14449541; Offset: 1450833928476476016
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834380028, nextTick: 60001, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834380054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834389441923715; DSPS: 15104916; Offset: 1450833928476469614
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834409442766999; DSPS: 15760303; Offset: 1450833928476488923
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834429443613836; DSPS: 16415691; Offset: 1450833928476481268
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834440033, nextTick: 59987, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834440042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834449444083576; DSPS: 17071066; Offset: 1450833928476493244
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834469444526709; DSPS: 17726441; Offset: 1450833928476478614
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834489445395106; DSPS: 18381829; Offset: 1450833928476492519
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834500038, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834500046, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834509446317056; DSPS: 19037219; Offset: 1450833928476498941
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834529446744295; DSPS: 19692594; Offset: 1450833928476468417
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834549448174604; DSPS: 20348000; Offset: 1450833928476494917
,I/ActivityManager(  968): Killing 4680:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79308 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834560038, nextTick: 59980, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834560047, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834569449544878; DSPS: 21003405; Offset: 1450833928476491900
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834589450391760; DSPS: 21658793; Offset: 1450833928476484290
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834609451263402; DSPS: 22314181; Offset: 1450833928476501440
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834620028, nextTick: 59996, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834620054, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834629452191565; DSPS: 22969572; Offset: 1450833928476483558
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834649452647434; DSPS: 23624947; Offset: 1450833928476481663
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834669453515313; DSPS: 24280335; Offset: 1450833928476495050
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834680050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834680053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834689454409416; DSPS: 24935725; Offset: 1450833928476473625
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834709454864926; DSPS: 25591099; Offset: 1450833928476501889
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834729456177852; DSPS: 26246502; Offset: 1450833928476502560
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834740056, nextTick: 59971, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834740059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834749457055557; DSPS: 26901891; Offset: 1450833928476495255
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834769457513907; DSPS: 27557266; Offset: 1450833928476495841
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  968): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  968): Done.
,D/QcConnectivityService(  968): Setting timer for 720seconds
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834789458405926; DSPS: 28212656; Offset: 1450833928476472333
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834800031, nextTick: 59992, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834800040, nextTick: 59991, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834809458864633; DSPS: 28868031; Offset: 1450833928476473276
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834829459325110; DSPS: 29523406; Offset: 1450833928476475989
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834849460190991; DSPS: 30178794; Offset: 1450833928476487378
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834860037, nextTick: 59982, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834860046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834869460639711; DSPS: 30834169; Offset: 1450833928476478335
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834889461500515; DSPS: 31489557; Offset: 1450833928476484646
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834909462416612; DSPS: 32144947; Offset: 1450833928476485216
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834920038, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834920041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834929462864780; DSPS: 32800322; Offset: 1450833928476475620
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834949463305247; DSPS: 33455696; Offset: 1450833928476488841
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834969464661517; DSPS: 34111101; Offset: 1450833928476471820
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834980031, nextTick: 59984, mDrawingTime: 7
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450834980043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450834989465116861; DSPS: 34766475; Offset: 1450833928476499918
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835009465561613; DSPS: 35421850; Offset: 1450833928476486906
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835029466430010; DSPS: 36077238; Offset: 1450833928476500811
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835040040, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835040045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835049467931436; DSPS: 36732647; Offset: 1450833928476506876
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835069468350684; DSPS: 37388021; Offset: 1450833928476498878
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835089469216880; DSPS: 38043409; Offset: 1450833928476510582
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835100029, nextTick: 59999, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835100054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835109469679089; DSPS: 38698785; Offset: 1450833928476484509
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835129470121893; DSPS: 39354159; Offset: 1450833928476500067
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835149470576102; DSPS: 40009534; Offset: 1450833928476496513
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835160038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835160041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835169471025669; DSPS: 40664909; Offset: 1450833928476488316
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835189471477961; DSPS: 41320284; Offset: 1450833928476482844
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835209471929882; DSPS: 41975659; Offset: 1450833928476477002
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835220043, nextTick: 59986, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835220046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835229472389219; DSPS: 42631034; Offset: 1450833928476478575
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835249472846155; DSPS: 43286409; Offset: 1450833928476477747
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835269473696427; DSPS: 43941797; Offset: 1450833928476473527
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835280036, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835280038, nextTick: 59993, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835289474142045; DSPS: 44597171; Offset: 1450833928476491899
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835309475003560; DSPS: 45252559; Offset: 1450833928476498922
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835329475919813; DSPS: 45907949; Offset: 1450833928476499647
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835340040, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835340045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835349476792144; DSPS: 46563338; Offset: 1450833928476486969
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835369479167572; DSPS: 47218776; Offset: 1450833928476482026
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835389479624803; DSPS: 47874151; Offset: 1450833928476481493
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835400038, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835400047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835409480088635; DSPS: 48529526; Offset: 1450833928476487561
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835429480546166; DSPS: 49184901; Offset: 1450833928476487329
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835449481423078; DSPS: 49840290; Offset: 1450833928476479231
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835460037, nextTick: 59989, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835460041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835469481889701; DSPS: 50495665; Offset: 1450833928476488090
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835489482337034; DSPS: 51151040; Offset: 1450833928476477659
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835509483186971; DSPS: 51806427; Offset: 1450833928476503622
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835520041, nextTick: 59983, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835520047, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835529483669565; DSPS: 52461803; Offset: 1450833928476497935
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  968): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  968): Done.
,D/QcConnectivityService(  968): Setting timer for 720seconds
,D/GCM     ( 1538): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/EventLogService( 1900): Aggregate from 1450834051200 (log), 1450833739305 (data)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835549484564133; DSPS: 53117193; Offset: 1450833928476476975
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835569485421139; DSPS: 53772581; Offset: 1450833928476479489
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835580036, nextTick: 59992, mDrawingTime: 3
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835580039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835589485880120; DSPS: 54427956; Offset: 1450833928476480706
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835609486341584; DSPS: 55083331; Offset: 1450833928476484407
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835629487796506; DSPS: 55738738; Offset: 1450833928476505003
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835640035, nextTick: 59985, mDrawingTime: 5
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835640044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835649488253861; DSPS: 56394114; Offset: 1450833928476474076
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835669488709386; DSPS: 57049488; Offset: 1450833928476502355
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835689489591021; DSPS: 57704877; Offset: 1450833928476498980
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835700029, nextTick: 59984, mDrawingTime: 8
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835700062, nextTick: 59969, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835709490049440; DSPS: 58360252; Offset: 1450833928476499636
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835729490490829; DSPS: 59015627; Offset: 1450833928476483261
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835749491457723; DSPS: 59671018; Offset: 1450833928476504110
,I/ProcessStatsService(  968): Prepared write state in 18ms,
,D/LocationManagerService(  968): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  968): Pruning old procstats: /data/system/procstats/state-2015-12-22-01-49-47.bin
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835760025, nextTick: 59998, mDrawingTime: 6
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835760052, nextTick: 59979, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835769491900293; DSPS: 60326393; Offset: 1450833928476488917
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835789492763486; DSPS: 60981781; Offset: 1450833928476497617
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835809493227671; DSPS: 61637157; Offset: 1450833928476473521
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1142): handleTimeUpdate
,D/KeyguardModel( 1142): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835820036, nextTick: 59991, mDrawingTime: 4
,D/Clock   ( 1142): Clock updated, drawingStartTime : 1450835820039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835829493674785; DSPS: 62292531; Offset: 1450833928476493389
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1450835849494112520; DSPS: 62947906; Offset: 1450833928476473360
,TIME-OUT KILL (timeout was 1800000ms)
```
