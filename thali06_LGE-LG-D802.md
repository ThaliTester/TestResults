#### Test 56151093f3290d6_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
V/ConfigFetchTask( 1945): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WN08xoMq32NBCMZyv7AfBdyQvOu3O9I38MiEUqOw47DnYEoDzz7fMlPMmoheIPa7d8tLFDl0XSx9l14Do9VKVlSYNvRFqYBiaPXBj3dWRCxpqZ87OqqTShNthdCdlvv5Lt3AYJwyQQk9oyHrUmE5k4IXaOmha5HErcP9d-jSCu7KNRIjTtQKmermook5cQ_E-r0TS8
I/GoogleURLConnFactory( 1945): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1945): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1945): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1945): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1945): CP2 sync disabled
I/dalvikvm( 1945): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1945): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
D/dalvikvm( 1945): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
,W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/BaseAppContext( 1945): Using Auth Proxy for data requests.
W/GAV2    ( 4622): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  962): Killing 4070:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2}
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1945): GC_CONCURRENT freed 1533K, 22% free 19454K/24832K, paused 4ms+5ms, total 52ms
I/ConfigFetchService( 1945): fetch service done; releasing wakelock
I/ConfigFetchService( 1945): stopping self
D/AndroidRuntime( 4666): 
D/AndroidRuntime( 4666): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4666): CheckJNI is OFF
D/dalvikvm( 4666): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4666): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4666): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4666): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4666): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
D/dalvikvm( 4666): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Icing   ( 1945): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
D/Icing   ( 1945): Loaded CLD2 Version V2.0 - 20141016
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1218): Disconnected process message: 10
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
E/memtrack( 4666): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4666): failed to load memtrack module: -2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/WifiController(  962): battery changed pluggedType: 2
I/Icing   ( 1945): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4666): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4666
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (120 us)
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  962): GC_FOR_ALLOC freed 24142K, 52% free 28824K/59716K, paused 122ms, total 122ms
D/AndroidRuntime( 4666): Shutting down VM
D/UsbSettingsControl( 2613): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2613): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3953): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{43300530 stackId=1, 2 tasks}
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4666): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 3ms
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4689 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3953): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3953): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4689): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4689): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4689): Binding Chromium to the background looper Looper (main, tid 1) {42829fa0}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/chromium( 4689): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4689): Initializing chromium process, renderers=0
W/chromium( 4689): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4689): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4689): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4689): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4689): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4689): Remote Branch: 
I/Adreno-EGL( 4689): Local Patches: 
I/Adreno-EGL( 4689): Reconstruct Branch: 
I/dalvikvm( 4689): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4689): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4689): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4689): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4689): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4689): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4689): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4689): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4689): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4689): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4689): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4689): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4689): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4689): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4689): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4689): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4689): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4689): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/OpenGLRenderer( 4689): Enabling debug mode 0
,W/AwContents( 4689): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  962): IME STATUS OFF
W/AwContents( 4689): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 4689): Timeline: Activity_idle id: android.os.BinderProxy@4282b680 time:112543
I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +450ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4689): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4689): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4282f760
D/dalvikvm( 4689): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4282f760
D/jxcore_app_log( 4689): JniHelper::setJavaVM(0x416f9838), pthread_self() = 1631385400
D/JX-Cordova( 4689): jxcore cordova android initializing
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3} time:112869
D/ActivityManager(  962): no-history finish of ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{43423b08 ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2613): [AUTORUN] onStop()
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.450577 Y: -0.409134 Z: 9.793625 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450577 .y:-0.409134 .z:9.793625
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.460724 Y: -0.419235 Z: 9.789291 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460724 .y:-0.419235 .z:9.789291
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/dalvikvm( 4689): GC_CONCURRENT freed 2680K, 12% free 21972K/24832K, paused 2ms+1ms, total 42ms
,D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 317K, 11% free 22316K/24832K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.006MB for 42652-byte allocation
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 104K, 11% free 22322K/24876K, paused 25ms, total 25ms
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 126K, 11% free 22343K/24876K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.083MB for 95956-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 178K, 11% free 22378K/24972K, paused 25ms, total 25ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.164MB for 143930-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 252K, 11% free 22424K/25116K, paused 22ms, total 22ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.278MB for 215890-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 367K, 12% free 22499K/25328K, paused 23ms, total 23ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.454MB for 323830-byte allocation
D/dalvikvm( 4689): GC_FOR_ALLOC freed 566K, 12% free 22619K/25648K, paused 24ms, total 25ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 24.725MB for 485740-byte allocation
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/dalvikvm( 4689): GC_FOR_ALLOC freed 862K, 13% free 22795K/26124K, paused 25ms, total 25ms
D/dalvikvm( 4689): GC_FOR_ALLOC freed 1153K, 12% free 23038K/26124K, paused 31ms, total 32ms
D/dalvikvm( 4689): GC_FOR_ALLOC freed 181K, 12% free 22996K/26124K, paused 26ms, total 27ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 25.673MB for 1092904-byte allocation
D/dalvikvm( 4689): GC_CONCURRENT freed 1762K, 14% free 23442K/27192K, paused 2ms+3ms, total 31ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4689): GC_FOR_ALLOC freed 241K, 15% free 23360K/27192K, paused 25ms, total 26ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 26.549MB for 1639352-byte allocation
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/dalvikvm( 4689): GC_CONCURRENT freed 1901K, 17% free 23969K/28796K, paused 2ms+2ms, total 35ms
D/dalvikvm( 4689): GC_FOR_ALLOC freed 999K, 17% free 23940K/28796K, paused 26ms, total 26ms
I/dalvikvm-heap( 4689): Grow heap (frag case) to 27.897MB for 2459024-byte allocation
D/dalvikvm( 4689): GC_CONCURRENT freed 425K, 16% free 26315K/31200K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 4078K, 20% free 24972K/31200K, paused 31ms, total 31ms
,I/dalvikvm-heap( 4689): Grow heap (frag case) to 30.078MB for 3688532-byte allocation
,D/dalvikvm( 4689): GC_CONCURRENT freed 218K, 19% free 28466K/34804K, paused 2ms+4ms, total 35ms
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/dalvikvm( 4689): GC_FOR_ALLOC freed 4445K, 26% free 26095K/34804K, paused 31ms, total 31ms
,W/jxcore-log( 4689): Initializing JXcore engine
,W/jxcore-log( 4689): JXcore engine is ready
,D/dalvikvm( 4689): GC_CONCURRENT freed 418K, 17% free 28887K/34804K, paused 2ms+1ms, total 27ms
D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4689): WAIT_FOR_CONCURRENT_GC blocked 13ms
,W/jxcore-log( 4689): Starting JXcore engine
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/jxcore-log( 4689): Platform android
W/jxcore-log( 4689): 
,W/jxcore-log( 4689): Process ARCH arm
W/jxcore-log( 4689): 
,I/jxcore-log( 4689): JXcore Cordova bridge is ready!
I/jxcore-log( 4689): 
,W/jxcore-log( 4689): JXcore engine is started
,I/chromium( 4689): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4689): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4689): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/ActivityManager(  962): Killing 4151:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,I/jxcore-log( 4689): Toggling radios to true
I/jxcore-log( 4689): 
,D/BluetoothManagerService(  962): Message: 20
,D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43153d38:true
,D/BluetoothAdapter( 4689): enable(): BT is already enabled..!
D/WifiStateMachine(  962): handleMessage: E msg.what=131145
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DISCONNECT
I/jxcore-log( 4689): Radios toggled
I/jxcore-log( 4689): 
I/jxcore-log( 4689): My device name is: LGE-LG-D802
I/jxcore-log( 4689): 
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2023): TDLS: Tear down peers
,D/wpa_supplicant( 2023): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  962): New client listening to asynchronous messages
D/WifiService(  962): setWifiEnabled: true pid=4689, uid=10304
E/WifiService(  962): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  962): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  962): disconnect pid=4689, uid=10304
D/WifiService(  962): reconnect pid=4689, uid=10304
,D/wpa_supplicant( 2023): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 2023): wlan0: Deauthentication notification
D/wpa_supplicant( 2023): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2023): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2023): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2023): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 2023): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb799ad6c key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): wlan0: State: COMPLETED -> DISCONNECTED
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131146
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiNative-wlan0(  962): doBoolean: RECONNECT
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2023): Fast associate: Old scan results
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2023): wlan0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147460
D/WifiStateMachine(  962): processMsg: DisconnectingState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection lost
,D/WifiStateMachine(  962): Stopping DHCP and clearing IP
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
D/WifiP2pService(  962): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/DhcpStateMachine(  962): RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  962): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
,E/Parcel  (  492): Reading a NULL string not supported here.
,D/WifiHS20(  962): hidePasspointNotification off =false
D/QCNEA   (  492): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  492): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  492): |CAC| updateNetCfgInfo
V/QCNEA   (  492): |CAC| *********************************************
V/QCNEA   (  492): |CAC|                   Netconfig               
V/QCNEA   (  492): |CAC| *********************************************
V/QCNEA   (  492): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  492): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  492): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  492): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  492): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  492): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  492): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  492): |CAC| *********************************************
D/QCNEA   (  492): |CAC| Received bssid= 
D/QCNEA   (  492): |CAC| net type = 3
V/QCNEA   (  492): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  492): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  492): |CAC| 	ssid           =NG700
V/QCNEA   (  492): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  492): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  492): |CAC| *********************************************
D/QCNEA   (  492): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  492): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  492): |CAC| dispatchNetCfg: updating:0xb86ce8dc
D/QCNEA   (  492): |CAC| readCallback: read len:0, ret:-1, errno:11
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4758 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  264): RouteController
D/HyLog   ( 4758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4758): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
I/GAV2    ( 4622): Thread[GAThread,5,main]: No campaign data found.
V/        (  264): RouteController
V/        (  264): RouteController
,I/PCSuite ( 4758): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  264): RouteController
,W/NetworkManagementService(  962): route cmd failed: 
W/NetworkManagementService(  962): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  962): '
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  962): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  962): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x628526e8 clazz=0x6bf00001 iface=wlan0 mask=0x3
,D/PCSuite ( 4758): [StartReceiver][getUpdateNecessity]update = false
,D/QcConnectivityService(  962): resetConnections(wlan0, 3)
D/PCSuite ( 4758): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/NativeCrypto( 1562): Read error: ssl=0x639ed008: I/O error during system call, Connection timed out
V/NativeCrypto( 1562): SSL shutdown failed: ssl=0x639ed008: I/O error during system call, Broken pipe
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4796 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  962): Killing 3122:android.process.media/u0a23 (adj 15): empty #17
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4796): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4796): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4796): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4796): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4796): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4796): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4796): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4796): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4796): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4796): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4796): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4796): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 3912:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  962): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ConfigService( 1562): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Choreographer( 4689): Skipped 175 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4689): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  962): MasterInitialState.processMessage what=3
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :false
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2023): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 2023): wlan0: New scan results available
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2023): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2023): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2023): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2023): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2023): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb799c5a8  current_ssid=0x0
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_p,olicy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2023): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2023): wlan0: Automatic auth_alg selection: 0x1
,D/wpa_supplicant( 2023): RSN: PMKSA cache search - network_ctx=0xb799c5a8 try_opportunistic=0
D/wpa_supplicant( 2023): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2023): RSN: No PMKSA cache entry found,
,D/wpa_supplicant( 2023): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2023): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using PTK CCMP,
D/wpa_supplicant( 2023): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2023): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb799b590 (mode change),
D/wpa_supplicant( 2023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb799b590,
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2023): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2023):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023):   * freq=2412
D/wpa_supplicant( 2023):   * SSID - hexdump(len=5): 4e 47 37 30 30,
D/wpa_supplicant( 2023):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
D/wpa_supplicant( 2023):   * Auth Type 0
D/wpa_supplicant( 2023):   * WPA Versions 0x2
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 c2:ff:d4:d3:aa:48]
D/wpa_supplicant( 2023): nl80211: Connect request send successfully
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2023): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 a0:c5:62:7a:49:97]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt,
D/WifiStateMachine(  962): processMsg: SupplicantStartedState,
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2023): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
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
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
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
D/wpa_supplicant( 20,23): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4284c3c0
,D/WifiStateMachine(  962): handleMessage: X
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 dc 59 a8 ae 12 ee 24 98 bc 66 d5 9d 78 e7 67 ...
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): dc 59 a8 ae 12 ee 24 98 bc 66 d5 9d 78 e7 67 95 84 83 2e f7 64 43 c1 39 fe 71 75 b0 4c bd 2a b5
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 dc 59 a8 ae 12 ee 24 98 bc 66 d5 9d 78 e7 67 ...
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2023): Get randomness: len=32 entropy=8
D/wpa_supplicant( 2023): WPA: Renewed SNonce - hexdump(len=32): 16 00 6a 4c 21 a1 18 3f 1f 18 60 27 1c 14 f5 f7 fb 5b d9 f0 cc d3 4d 07 23 8b c9 09 fc ff c3 26
D/wpa_supplicant( 2023): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): WPA: Nonce1 - hexdump(len=32): 16 00 6a 4c 21 a1 18 3f 1f 18 60 27 1c 14 f5 f7 fb 5b d9 f0 cc d3 4d 07 23 8b c9 09 fc ff c3 26
D/wpa_supplicant( 2023): WPA: Nonce2 - hexdump(len=32): dc 59 a8 ae 12 ee 24 98 bc 66 d5 9d 78 e7 67 95 84 83 2e f7 64 43 c1 39 fe 71 75 b0 4c bd 2a b5
D/wpa_supplicant( 2023): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2023): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): cd b4 c4 fc 69 37 9c a3 6e 8a b6 12 a7 35 97 df
,D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 16 00 6a 4c 21 a1 18 3f 1f 18 60 27 1c 14 f5 ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 dc 59 a8 ae 12 ee 24 98 bc 66 d5 9d 78 e7 67 ...
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): dc 59 a8 ae 12 ee 24 98 bc 66 d5 9d 78 e7 67 95 84 83 2e f7 64 43 c1 39 fe 71 75 b0 4c bd 2a b5
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 9e 0e 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): b6 f4 eb 37 6d 21 1c 42 19 17 77 17 99 a2 8c 78
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 dc 59 a8 ae 12 ee 24 98 bc 66 d5 9d 78 e7 67 ...
D/wpa_supplicant( 2023): RSN: encrypted key data - hexdump(len=56): b2 5a ef 3d 49 de 8a c8 f5 d5 2a 00 32 af 85 a6 27 93 48 fd 78 3c cf 1e 94 b3 98 7a a4 c5 34 1a ...
D/wpa_supplicant( 2023): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 8d 6d ...
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 56 aa e6 42 2d bf 0f 0f 57 fa 4c d3 79 b7 71 c1
,D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
,D/wpa_supplicant( 2023): wlan0: WPA: Installing PTK to the driver,
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb799bc54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2023): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 2023): WPA: RSC - hexdump(len=6): 9e 0e 00 00 00 00
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6faf03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2023):    broadcast key
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/wpa_supplicant( 2023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2023): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2023): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): EAPOL authentication completed successfully
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): Network connection established
I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/WifiNative-wlan0(  962): doString: STATUS
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2023): wlan0: Control interface command 'STATUS'
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  962):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  962): ssid=NG700
D/WifiNative-wlan0(  962): id=0
D/WifiNative-wlan0(  962): mode=station
D/WifiNative-wlan0(  962): pairwise_cipher=CCMP
D/WifiNative-wlan0(  962): group_cipher=CCMP
D/WifiNative-wlan0(  962): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  962): wpa_state=COMPLETED
D/WifiNative-wlan0(  962): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  962): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-25ms what=147462 obj=android.net.wifi.StateChangeResult@4327fa10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/DhcpStateMachine(  962): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): handleMessage: X
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
,D/WifiStateMachine(  962): ObtainingIpState{ when=-22ms what=147462 obj=android.net.wifi.StateChangeResult@432e0bf8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-22ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,I/ActivityManager(  962): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4840 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  962): handleMessage: X
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/HyLog   ( 4840): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4840): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4840): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4840): DownloadService onCreate
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4840): in removeSpuriousFiles
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/eas_req ( 4602): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4840): DownloadService onStartCommand
,V/DownloadManager( 4840): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/DownloadManager( 4840): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@42873b18 on behalf of 4840
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@42875cc8 on behalf of 4840
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  962):    returned null
I/DownloadManager( 4840): in trimDatabase
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/DownloadManager( 4840): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
D/WifiP2pService(  962): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43271250 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43271250 target=com.android.internal.util.StateMachine$SmHandler }
V/DownloadManager( 4840): DownloadService onDestroy
D/CommandListener(  264): Setting iface cfg
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@42878188 on behalf of 4840
D/CommandListener(  264): Trying to bring up wlan0
D/WifiStateMachine(  962): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
I/LgeMiscReceiver( 4323): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4323): action = android.net.conn.CONNECTIVITY_CHANGE
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/LgeMiscReceiver( 4323): networkInfo.isConnected() = false
W/linker  ( 4602): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/HtmlEditor( 4602): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4602): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4602): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): DHCP successful
I/dalvikvm( 4602): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/HtmlEditor( 4602): register_HtmlEditor, Success
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/HtmlEditor( 4602): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
D/HtmlEditor( 4602): register_HtmlEditorTimer, Success
D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/HtmlEditor( 4602): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4602): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4602): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4602): register_HtmlEditorFont, Success
D/HtmlEditor( 4602): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4602): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4602): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4602): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4602): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4602): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4602): JNI_OnLoad Success
I/HubEmail( 4602): JNI_OnLoad()
I/HubEmail( 4602): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4602): registerNatives()
I/HubEmail( 4602): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4602): registerNativeMethods()
I/HubEmail( 4602): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/WifiStateMachine(  962): VerifyingLinkState what=131212 NOT_HANDLED
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
,E/Parcel  (  492): Reading a NULL string not supported here.
I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4863 uid=10052 gids={50052, 3003}
,W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): CaptivePortalCheckState enter
D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine(  962): handleMessage: X
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
,E/Parcel  (  492): Reading a NULL string not supported here.
,D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,I/ActivityManager(  962): Killing 4360:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  492): Reading a NULL string not supported here.
,E/Parcel  (  492): Reading a NULL string not supported here.
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  492): Reading a NULL string not supported here.
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4863): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  264): RouteController
V/LGRssiData( 4863): [loadRssi] File not exist 
V/LGRssiData( 4863): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4863): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4863): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4863): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4863): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4863): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4863): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4863): [getValue] FEATURE key : vzw_roaming_state, value : null
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4895 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  962): Killing 4529:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  492): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  492): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  492): |CAC| updateNetCfgInfo
V/QCNEA   (  492): |CAC| *********************************************
V/QCNEA   (  492): |CAC|                   Netconfig               
V/QCNEA   (  492): |CAC| *********************************************
V/QCNEA   (  492): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  492): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  492): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  492): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  492): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  492): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  492): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  492): |CAC| *********************************************
D/QCNEA   (  492): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  492): |CAC| net type = 1
V/QCNEA   (  492): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  492): |CAC| Received ssid= NG700
V/QCNEA   (  492): |CAC| 	ssid           =NG700
V/QCNEA   (  492): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  492): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  492): |CAC| *********************************************
D/QCNEA   (  492): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  492): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  492): |CAC| dispatchNetCfg: updating:0xb86ce8dc
D/QCNEA   (  492): |CAC| readCallback: read len:0, ret:-1, errno:11
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/PhoneMonitor( 4863): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4863): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4895): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4895): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4895): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1945): Checking schedule, now: 1452862935957 next: 1452862877909
,I/CheckinService( 1945): active receiver: enabled
,I/CheckinService( 1945): Preparing to send checkin request
,I/EventLogService( 1945): Accumulating logs since 1452862845252
,I/CheckinRequestBuilder( 1945): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1945): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4910 uid=10066 gids={50066, 4002, 3003, 1028}
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/HyLog   ( 4910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4910): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4910): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  962): Killing 4561:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4929 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4929): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4929): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1562): GC_EXPLICIT freed 1044K, 29% free 17809K/24832K, paused 1ms+4ms, total 51ms
,D/LGDMSGCM( 4929): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4943 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  962): Killing 4588:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/HyLog   ( 4943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4943): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4943): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 4943): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4943): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 4943): intf.getDisplayName() = lo
,I/Wireless_Storage( 4943): intf.getDisplayName() = sit0
I/Wireless_Storage( 4943): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4943): intf.getDisplayName() = teql0
I/Wireless_Storage( 4943): intf.getDisplayName() = wlan0
D/NFS     ( 4943): interface name:wlan0 name:wlan0
D/NFS     ( 4943): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4943): interface name:wlan0 name:wlan0
D/NFS     ( 4943): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4943): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4956 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 4200:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4956): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4956): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4956): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 4956): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1945): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x430be150: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4974 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4974): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4974): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,W/dalvikvm( 4974): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4974): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4974): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4974): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4974): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4974): install
,I/MultiDex( 4974): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+2ms, total 15ms
,I/MultiDex( 4974): loading existing secondary dex files
,I/MultiDex( 4974): load found 3 secondary dex files
,I/MultiDex( 4974): install done
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
D/dalvikvm( 4974): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4974): VFY: unable to resolve instance field 61
,D/dalvikvm( 4974): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 4974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4974): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4974): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4974): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4974): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4974): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4974): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283d890
,D/dalvikvm( 4974): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283d890
,D/dalvikvm( 4974): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283d890, skipping init
,D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283d890
D/dalvikvm( 4974): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283d890
,V/JNIHelp ( 4974): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283d890
,D/dalvikvm( 4974): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4283d890
D/dalvikvm( 4974): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283d890
,D/dalvikvm( 4974): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4283d890
,V/WebViewChromium( 4956): Binding Chromium to the main looper Looper (main, tid 1) {428365f0}
,I/chromium( 4956): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4956): Initializing chromium process, renderers=0
,W/chromium( 4956): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4956): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4956): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4956): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4956): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4956): Remote Branch: 
I/Adreno-EGL( 4956): Local Patches: 
I/Adreno-EGL( 4956): Reconstruct Branch: 
,I/ProviderInstaller( 4974): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 4974): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
,W/dalvikvm( 4974): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4974): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4974): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4974): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4974): VFY: replacing opcode 0x6e at 0x0201
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  962): GC_EXPLICIT freed 2080K, 51% free 29710K/59716K, paused 2ms+7ms, total 89ms
,I/NSApplication( 4956): Starting up...
,I/ActivityManager(  962): Killing 4216:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/WVCdm   (  270): Instantiating CDM.
,I/WVCdm   (  270): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  270): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  270): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  270): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e4a000
,E/DrmWidevineDash(  270): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e4a000
,D/DrmWidevineDash(  270): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  270): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  270): calling OEMCrypto_IsKeyboxValid...
,D/QRemote ( 4796): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4796): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/DrmWidevineDash(  270): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  270): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  270): CdmEngine::OpenSession
,D/DrmWidevineDash(  270): calling OEMCrypto_OpenSession...
,D/QRemote ( 4796): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4796): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DrmWidevineDash(  270): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_OpenSession returns 0
I/WVCdm   (  270): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  270): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  270): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/QRemote ( 4796): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4796): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4758): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4758): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/DrmWidevineDash(  270): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GetDeviceID...
,D/QRemote ( 4796): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4796): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4796): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4796): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/DrmWidevineDash(  270): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateNonce. SID = 1
,D/GCM     ( 1562): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/DrmWidevineDash(  270): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  270): PrepareKeyRequest: nonce=947246277
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/AuthorizationBluetoothService( 1562): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,E/AuthorizationBluetoothService( 1562): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1945): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
D/WearableService( 1758): callingUid 10006, callindPid: 1758
,D/DhcpStateMachine(  962): RunningState
,E/MDM     ( 1426): [62] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1945): Restart initialization of location
,D/wpa_supplicant( 2023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2023): EAPOL: disable timer tick
D/dalvikvm( 4974): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a72350
D/dalvikvm( 4974): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a72350
,D/dalvikvm( 4974): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a72350, skipping init
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
D/WVCdm   (  270): PrepareKeyRequest: nonce=2158768765
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  270): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/DrmWidevineDash(  270): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  270): CdmEngine::CloseSession
,D/DrmWidevineDash(  270): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  270): OEMCrypto_CloseSession returns 0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,W/Settings( 4974): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4974): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5045): DexOpt: load 4ms, verify+opt 9ms, 128132 bytes
,D/dalvikvm( 4974): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4974): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 111ms
,I/Adreno-EGL( 4974): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4974): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4974): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4974): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4974): Remote Branch: 
I/Adreno-EGL( 4974): Local Patches: 
I/Adreno-EGL( 4974): Reconstruct Branch: 
,E/ThermalEngine(  286): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Adreno-EGL( 4974): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4974): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4974): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4974): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4974): Remote Branch: 
I/Adreno-EGL( 4974): Local Patches: 
I/Adreno-EGL( 4974): Reconstruct Branch: 
,I/Adreno-EGL( 4974): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4974): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4974): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4974): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4974): Remote Branch: 
I/Adreno-EGL( 4974): Local Patches: 
I/Adreno-EGL( 4974): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1945): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1945): Sending checkin request (11461 bytes)
,D/GCM     ( 1562): Connected
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/GCM     ( 1562): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1945): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1945): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x44f9f638: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/CheckinRequestBuilder( 1945): awaiting user notification for token
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/CheckinRequestBuilder( 1945): Classify the device as Phone.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/CheckinTask( 1945): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/CheckinService( 1945): Checking schedule, now: 1452862938499 next: 1453440334472
I/CheckinService( 1945): active receiver: disabled
,D/GCM     ( 1562): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
E/Parcel  (  492): Reading a NULL string not supported here.
,E/Parcel  (  492): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4284c3c0
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/SIMObserver( 2976): simInfo1
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4037): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4037): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4037): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4037): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4037): handleAsyncCustNotification do not startCustService
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4840): DownloadService onCreate
D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
D/eas_req ( 4602): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 4840): in removeSpuriousFiles
V/DownloadManager( 4840): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@4287d8a0 on behalf of 4840
I/DownloadManager( 4840): in trimDatabase
V/DownloadManager( 4840): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@4287ecb0 on behalf of 4840
V/DownloadManager( 4840): DownloadService onStartCommand
I/LgeMiscReceiver( 4323): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4323): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4840): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4323): networkInfo.isConnected() = false
W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4863): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4863): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@42880f40 on behalf of 4840
D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4840): DownloadService onDestroy
D/LGDMSGCM( 4929): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4943): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4943): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ContextImpl( 4929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4284c3c0
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4840): DownloadService onCreate
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4840): in removeSpuriousFiles
,V/DownloadManager( 4840): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4323): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4323): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4323): networkInfo.isConnected() = true
D/PhoneState( 4323): setPdpRejectCasuse : false
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@42885660 on behalf of 4840
,V/DownloadManager( 4840): DownloadService onStartCommand
,V/DownloadManager( 4840): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 4863): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4863): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@42887b80 on behalf of 4840
,I/DownloadManager( 4840): in trimDatabase
,V/DownloadManager( 4840): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4840): DownloadService onDestroy
,V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@428893f8 on behalf of 4840
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4929): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4943): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4943): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1218): Disconnected process message: 10
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4037): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
,D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4284c3c0
,D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4037): begin check event
,I/AppUp4:CustModeStarterReceiver( 4037): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4840): DownloadService onCreate
,D/EAS     ( 4602): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4323): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4323): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4323): networkInfo.isConnected() = true
,D/PhoneState( 4323): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4863): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4863): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2862): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4929): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 4943): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4943): CONNECT : WIFI_CONNECT
,I/DownloadManager( 4840): in removeSpuriousFiles
,V/DownloadManager( 4840): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Settings( 4602): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 2862): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LGDMClient( 2862): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@4288ceb8 on behalf of 4840
V/DownloadManager( 4840): DownloadService onStartCommand
V/DownloadManager( 4840): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@4288f988 on behalf of 4840
I/DownloadManager( 4840): in trimDatabase
V/DownloadManager( 4840): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@428909a8 on behalf of 4840
E/LGDMClient( 2862): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2862): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2862): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2862): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4840): DownloadService onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1218): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4956): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  962): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/ActivityManager(  962): Killing 4233:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  962): Killing 4622:com.google.android.apps.docs/u0a73 (adj 15): empty #18
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.445419 Y: -0.417435 Z: 9.798279 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.445419 .y:-0.417435 .z:9.798279
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/ActivityManager(  962): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5171 uid=10050 gids={50050, 3003, 1028, 1015}
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.450089 Y: -0.417664 Z: 9.800949 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450089 .y:-0.417664 .z:9.800949
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/HyLog   ( 5171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5171): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 5171): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 5171): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5171): VFY: replacing opcode 0x6e at 0x000b
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 5171): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 5171): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 5171): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5171): VFY: replacing opcode 0x6e at 0x004f
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5171): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/Finsky  ( 5171): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings( 5171): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5171): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5171): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5171): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5171): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 5171): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5171): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5171): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 5171): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5171): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 5171): VFY: replacing opcode 0x6e at 0x029a
,V/DownloadManager( 4840): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4840): created cursor android.database.sqlite.SQLiteCursor@42895c30 on behalf of 5171
I/dalvikvm( 5171): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5171): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5171): VFY: replacing opcode 0x6e at 0x001a
,I/dalvikvm( 5171): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 5171): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5171): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 5171): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5171): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5171): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5171): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 5171): Total arena pages for JIT: 11
,I/dalvikvm( 5171): Total arena pages for JIT: 12
I/dalvikvm( 5171): Total arena pages for JIT: 13
,I/dalvikvm( 5171): Total arena pages for JIT: 14
,D/Finsky  ( 5171): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5171): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  962): Killing 4758:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/Finsky  ( 5171): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 5171): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5171): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5171): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5171): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  962): GC_EXPLICIT freed 1894K, 51% free 29733K/59716K, paused 4ms+10ms, total 142ms
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1562): GC_EXPLICIT freed 1270K, 29% free 17813K/24832K, paused 2ms+3ms, total 33ms
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5171): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5171): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5171): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5171): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5171): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5241 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "smsto"
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator(  962): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) },
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 3953): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/SlideAside( 3953): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
D/HyLog   ( 5241): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5241): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5241): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1426): DISABLE
I/Babel   ( 5241): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5241): MmsConfig.loadMmsSettings
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/MediaCodecList( 5241): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5241): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/Babel   ( 5241): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 5241): MmsConfig.loadFromDatabase
I/MediaCodecList( 5241): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5241): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5241): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5241): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5241): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5241): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5241): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5241): MmsConfig.loadFromResources
,E/Babel   ( 5241): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5241): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5241): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LocationProviderProxy(  962): applying state to connected service
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5241): [loadRssi] File not exist 
V/LGRssiData( 5241): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 5241): [loadFeatureFromXml] *** start feature loading from xml
,D/LocationProviderProxy(  962): applying state to connected service
,V/TelephonyAutoProfiling( 5241): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5241): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5241): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4037): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4037): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4037): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4037): onReceive
D/AppUp4:CustFacade( 4037): Context : android.app.ReceiverRestrictedContext@4284c3c0
D/AppUp4:CustFacade( 4037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4037): isOpenOperator : true
,D/AppUp4:CustFacade( 4037): isPhone : true
,I/LicenseContentProvider( 2976): start selecting data
,D/SIMObserver( 2976): simInfo1
,I/AppUp4:EulaManager( 4037): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4037): begin check event
D/AppUp4:Utils( 4037): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4037): Event For Nothing, skip.
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5288 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5288): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5288): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5288): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5288): BUILD Country: EU
,I/SystemConfig( 5288): BUILD Operator: OPEN
,I/ActivityManager(  962): Killing 4796:com.lge.qremote/u0a96 (adj 15): empty #17
I/SystemConfig( 5288): systemFeature RCS result false
D/SystemConfig( 5288): refreshRcsSupport() :false
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5305 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5305): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): Killing 4602:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  962): Killing 4863:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/IcingCorporaProvider( 2683): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1945): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1945): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  962): Delaying start of: ServiceRecord{447d03c0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Icing   ( 1945): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1945): GC_CONCURRENT freed 1887K, 22% free 19549K/24832K, paused 2ms+3ms, total 34ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2683): UpdateCorporaTask done [took 234 ms] updated apps [took 234 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV4    ( 5241): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
,D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8171 usec
,D/qcom_sensors_hal(  962): hal_acquire_resources
,I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.449646 Y: -0.426605 Z: 9.793182 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.449646 .y:-0.426605 .z:9.793182
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.457764 Y: -0.426285 Z: 9.811905 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.457764 .y:-0.426285 .z:9.811905
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Sensors (  466): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.474930 Y: -0.424423 Z: 9.812592 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.474930 .y:-0.424423 .z:9.812592
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.471375 Y: -0.418411 Z: 9.791733 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471375 .y:-0.418411 .z:9.791733
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.467773 Y: -0.411346 Z: 9.782700 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467773 .y:-0.411346 .z:9.782700
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.471588 Y: -0.421249 Z: 9.802505 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.471588 .y:-0.421249 .z:9.802505
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43e07a48)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
I/WindowManager(  962): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb839a450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.450867 Y: -0.404434 Z: 9.801407 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450867 .y:-0.404434 .z:9.801407
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  962): handleScreenStateChanged: true
,D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131127
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=132097
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/WifiServiceExtension(  962): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2023): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
,V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4336f850 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,E/SlideAside( 3953): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1826): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:2:34
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3953): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1826): 2 : This is isUpdating : false
D/WeatherAncestor( 1826): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:2:34
D/WeatherService( 1826): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1826): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1826): 2 : shouldTimeTickRegistered : false
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
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
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 412ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452862955248, nextTick: 24785, mDrawingTime: 0
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452862955292, nextTick: 24740, mDrawingTime: 0
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,D/WeatherService( 1826): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:2:35
,D/WeatherService( 1826): 2 : ACTION screen on
,D/WeatherService( 1826): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/WeatherService( 1826): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:2:35
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
,E/Parcel  (  492): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
,I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.450302 Y: -0.431259 Z: 9.796082 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450302 .y:-0.431259 .z:9.796082
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
,D/KeyguardViewManager( 1143): onScreenTurnedOff()
D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
D/UsbSettings( 2613): [AUTORUN] onDestroy() : getDefaultFunction =boot
,I/LGImmersionVibrator(  962): Vibrator off
D/WifiStateMachine(  962): handleScreenStateChanged: false
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
D/WifiStateMachine(  962): processMsg: DriverStartedState
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
V/UsbSettings( 2613): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{43be3df0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/VolumeVibrator( 1157): clear
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{42bf2d68 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{43300530 stackId=1, 1 tasks}
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
E/Parcel  (  492): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WeatherService( 1826): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:2:35
D/WeatherService( 1826): 2 : ACTION screen off
D/WeatherService( 1826): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:2:35
D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/NfcService( 1475): NFC-C OFF
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  466): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,E/ThermalEngine(  286): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862963163132401; DSPS: 4948162; Offset: 1452862812157211991
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1562): Vacuum at: now=1452862964694 tag=VacuumService
,I/GoogleURLConnFactory( 1562): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1562): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1562): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1562): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1562): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1562): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 5171): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5171): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1562):  no longer exists, so no auth token.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1562): No account for auth token provided
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452862980055, nextTick: 59974, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452862980059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452862983164473852; DSPS: 5603566; Offset: 1452862812157210669
,I/EventLogService( 1945): Aggregate from 1452862935985 (log), 1452861190947 (data)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,D/WifiController(  962): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  962): battery changed pluggedType: 2
D/HeadsetStateMachine( 1218): Disconnected process message: 10
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 283 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863003166884158; DSPS: 6259005; Offset: 1452862812157210086
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863023168221493; DSPS: 6914408; Offset: 1452862812157235165
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 5 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 dc:4a:3e:0f:c2:f1]
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863040039, nextTick: 59986, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863040044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863043169541174; DSPS: 7569812; Offset: 1452862812157212073
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863063170397989; DSPS: 8225200; Offset: 1452862812157214396
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863083170846263; DSPS: 8880574; Offset: 1452862812157235424
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863100048, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863100051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863103171797453; DSPS: 9535965; Offset: 1452862812157240569
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863123172678018; DSPS: 10191354; Offset: 1452862812157236124
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 6 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 7 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 4 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 a0:c5:62:7a:49:97]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 06:7c:34:12:7f:81]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
,D/dalvikvm( 2670): GC_CONCURRENT freed 7798K, 33% free 16761K/24832K, paused 2ms+1ms, total 34ms
,D/dalvikvm( 2670): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  962): GC_EXPLICIT freed 2135K, 50% free 29912K/59716K, paused 3ms+8ms, total 105ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863143173793427; DSPS: 10846751; Offset: 1452862812157222383
,I/LocationManagerService(  962): remove 43257c20
,D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863160043, nextTick: 59985, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863160047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863163174249044; DSPS: 11502126; Offset: 1452862812157220236
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863183180825339; DSPS: 12157701; Offset: 1452862812157235252
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863203181676217; DSPS: 12813089; Offset: 1452862812157231637
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863220058, nextTick: 59973, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863220059, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863223182576730; DSPS: 13468479; Offset: 1452862812157216623
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x432341b0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863243186258962; DSPS: 14123959; Offset: 1452862812157236746
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1562): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1562): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1562): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1562): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1562): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1562): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1562): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1562): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 5171): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5171): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5171): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5171): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5171): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5171): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5171): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 5171): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 5171): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 5171): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863263187892704; DSPS: 14779373; Offset: 1452862812157222538
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863280048, nextTick: 59980, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863280052, nextTick: 59980, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863283188336915; DSPS: 15434748; Offset: 1452862812157208986
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863303188788887; DSPS: 16090122; Offset: 1452862812157233712
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863323192015494; DSPS: 16745588; Offset: 1452862812157225455
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863340039, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863340045, nextTick: 59966, mDrawingTime: 7
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863343193375225; DSPS: 17400993; Offset: 1452862812157211895
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863363194937666; DSPS: 18056404; Offset: 1452862812157217940
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863383196835263; DSPS: 18711826; Offset: 1452862812157223447
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863400040, nextTick: 59988, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863400042, nextTick: 59965, mDrawingTime: 10
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863403198177235; DSPS: 19367230; Offset: 1452862812157222646
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863423199517904; DSPS: 20022634; Offset: 1452862812157220541
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863443200906125; DSPS: 20678039; Offset: 1452862812157235471
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863460041, nextTick: 59984, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863460044, nextTick: 59986, mDrawingTime: 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863463202515024; DSPS: 21333452; Offset: 1452862812157226939
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863483204073193; DSPS: 21988863; Offset: 1452862812157228711
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863503205464643; DSPS: 22644269; Offset: 1452862812157216352
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863520049, nextTick: 59977, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863520053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863523207489688; DSPS: 23299695; Offset: 1452862812157227237
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863543208840514; DSPS: 23955099; Offset: 1452862812157235290
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863563210148579; DSPS: 24610502; Offset: 1452862812157231099
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863580050, nextTick: 59977, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863580053, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863583211584040; DSPS: 25265909; Offset: 1452862812157232234
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863603213144293; DSPS: 25921321; Offset: 1452862812157205573
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863623214648400; DSPS: 26576730; Offset: 1452862812157214318
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863640037, nextTick: 59990, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863640041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863643216079121; DSPS: 27232137; Offset: 1452862812157210713
,D/Finsky  ( 5171): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5171): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1562): GC_CONCURRENT freed 1779K, 28% free 18019K/24832K, paused 11ms+2ms, total 99ms
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5171): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1562): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1562): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1562): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1562): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1562): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1562): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 5171): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5171): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5171): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5171): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863663217458072; DSPS: 27887542; Offset: 1452862812157216373
,D/Finsky  ( 5171): [459] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5171): [1] 5.onFinished: Installation state replication succeeded.
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863683218832753; DSPS: 28542947; Offset: 1452862812157217763
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863700038, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863700041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863703220318734; DSPS: 29198355; Offset: 1452862812157238901
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863723221693882; DSPS: 29853761; Offset: 1452862812157210240
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863743223001063; DSPS: 30509163; Offset: 1452862812157235683
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863760048, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863760051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863763224524648; DSPS: 31164573; Offset: 1452862812157233389
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1218): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863783225993755; DSPS: 31819982; Offset: 1452862812157207134
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863803227887134; DSPS: 32475404; Offset: 1452862812157208424
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863820078, nextTick: 59954, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863820080, nextTick: 59953, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863823229266970; DSPS: 33130809; Offset: 1452862812157214969
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863843230588577; DSPS: 33786212; Offset: 1452862812157224320
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863863231957006; DSPS: 34441617; Offset: 1452862812157219458
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863880037, nextTick: 59982, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863880047, nextTick: 59985, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863883233336321; DSPS: 35097022; Offset: 1452862812157225482
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863903234644230; DSPS: 35752425; Offset: 1452862812157221135
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863923236025108; DSPS: 36407830; Offset: 1452862812157228722
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863940028, nextTick: 60000, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452863940055, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863943237685675; DSPS: 37063245; Offset: 1452862812157210822
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863963239013271; DSPS: 37718648; Offset: 1452862812157226162
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452863983240136128; DSPS: 38374045; Offset: 1452862812157219869
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864000037, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864000042, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864003241821016; DSPS: 39029460; Offset: 1452862812157226290
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864023243146320; DSPS: 39684864; Offset: 1452862812157208820
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864043244477198; DSPS: 40340267; Offset: 1452862812157227443
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864060052, nextTick: 59969, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864060059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864063245870368; DSPS: 40995673; Offset: 1452862812157216804
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864083247771350; DSPS: 41651095; Offset: 1452862812157225696
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864103249362747; DSPS: 42306507; Offset: 1452862812157230179
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864120071, nextTick: 59958, mDrawingTime: 3
D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864120073, nextTick: 59960, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864123250721230; DSPS: 42961912; Offset: 1452862812157215371
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864143252332420; DSPS: 43617325; Offset: 1452862812157209129
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864163253643767; DSPS: 44272728; Offset: 1452862812157208221
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864180030, nextTick: 60000, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864180048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864183255234488; DSPS: 44928140; Offset: 1452862812157212028
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864203257193231; DSPS: 45583564; Offset: 1452862812157217646
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864223258516140; DSPS: 46238967; Offset: 1452862812157228299
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864240037, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864240046, nextTick: 59984, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864243259918788; DSPS: 46894373; Offset: 1452862812157227138
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864263261227739; DSPS: 47549776; Offset: 1452862812157223833
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864283262842055; DSPS: 48205189; Offset: 1452862812157220718
,D/GCM     ( 1562): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864300041, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864300045, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864303264236005; DSPS: 48860595; Offset: 1452862812157210859
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864323265569226; DSPS: 49515998; Offset: 1452862812157231824
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864343267607240; DSPS: 50171425; Offset: 1452862812157225160
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864360051, nextTick: 59978, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864360054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864363268922701; DSPS: 50826828; Offset: 1452862812157228366
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864383270299517; DSPS: 51482233; Offset: 1452862812157231891
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864403271612217; DSPS: 52137636; Offset: 1452862812157232335
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864420051, nextTick: 59969, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864420059, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864423272996532; DSPS: 52793042; Offset: 1452862812157212841
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864443274569388; DSPS: 53448453; Offset: 1452862812157229301
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864463275892350; DSPS: 54103857; Offset: 1452862812157209489
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864480068, nextTick: 59955, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864480073, nextTick: 59958, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864483278122343; DSPS: 54759290; Offset: 1452862812157211699
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864503279434158; DSPS: 55414693; Offset: 1452862812157211258
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864523280743786; DSPS: 56070096; Offset: 1452862812157208630
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864540052, nextTick: 59974, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864540055, nextTick: 59973, mDrawingTime: 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864543282055497; DSPS: 56725499; Offset: 1452862812157208085
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864563283642208; DSPS: 57380911; Offset: 1452862812157207882
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864583284969804; DSPS: 58036314; Offset: 1452862812157223222
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864600038, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864600043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864603286865266; DSPS: 58691736; Offset: 1452862812157226595
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864623288504581; DSPS: 59347150; Offset: 1452862812157217960
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864643289852177; DSPS: 60002554; Offset: 1452862812157222783
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864660101, nextTick: 59929, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864660102, nextTick: 59929, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
I/ProcessStatsService(  962): Prepared write state in 82ms
,I/ProcessStatsService(  962): Pruning old procstats: /data/system/procstats/state-2016-01-14-19-30-00.bin
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864663291436805; DSPS: 60657966; Offset: 1452862812157220497
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864683292727057; DSPS: 61313368; Offset: 1452862812157229011
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864703294107050; DSPS: 61968773; Offset: 1452862812157235713
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864720031, nextTick: 59974, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1452864720049, nextTick: 59984, mDrawingTime: 0,
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1452864723295420949; DSPS: 62624177; Offset: 1452862812157206838
,TIME-OUT KILL (timeout was 1800000ms)
```
