#### Test 573480784751f5c_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
W/BaseAppContext( 1944): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GAV2    ( 4662): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  962): Killing 3655:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433443d8 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1944): fetch service done; releasing wakelock
I/ConfigFetchService( 1944): stopping self
D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1944): GC_CONCURRENT freed 1498K, 22% free 19473K/24832K, paused 3ms+4ms, total 42ms
D/AndroidRuntime( 4715): 
D/AndroidRuntime( 4715): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4715): CheckJNI is OFF
D/dalvikvm( 4715): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4715): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4715): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4715): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4715): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4715): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4715): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4715): failed to load memtrack module: -2
I/Icing   ( 1944): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1944): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4715): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4715
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433443d8 stackId=1, 2 tasks}
D/PermissionCache(  274): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (131 us)
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  962): GC_FOR_ALLOC freed 24233K, 54% free 27957K/59836K, paused 107ms, total 108ms
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/AndroidRuntime( 4715): Shutting down VM
D/UsbSettingsControl( 2610): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2610): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4715): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 5ms
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{433443d8 stackId=1, 2 tasks}
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433443d8 stackId=1, 2 tasks}
I/SlideAside( 4062): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 4062): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4730 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
D/SlideAside( 4062): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/Icing   ( 1944): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/HyLog   ( 4730): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4730): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4730): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4730): Binding Chromium to the background looper Looper (main, tid 1) {4285ab60}
I/chromium( 4730): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4730): Initializing chromium process, renderers=0
W/chromium( 4730): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4730): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4730): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4730): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4730): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4730): Remote Branch: 
I/Adreno-EGL( 4730): Local Patches: 
I/Adreno-EGL( 4730): Reconstruct Branch: 
I/dalvikvm( 4730): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4730): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4730): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4730): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4730): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4730): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4730): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4730): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4730): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4730): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4730): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4730): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4730): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4730): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4730): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4730): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4730): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4730): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4730): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4730): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
W/BaseRuntimeLoader( 4730): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4730): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4730): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4730): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1219): Disconnected process message: 10
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetStateMachine( 1219): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
D/OpenGLRenderer( 4730): Enabling debug mode 0
W/AwContents( 4730): nativeOnDraw failed; clearing to background color.
W/AwContents( 4730): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  962): IME STATUS OFF
I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +446ms
I/ActivityManager( 4730): Timeline: Activity_idle id: android.os.BinderProxy@4285c240 time:110201
D/JsMessageQueue( 4730): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4730): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42860848
D/dalvikvm( 4730): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42860848
D/jxcore_app_log( 4730): JniHelper::setJavaVM(0x41726838), pthread_self() = 1639638464
I/chromium( 4730): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/ActivityManager(  962): no-history finish of ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{42a1d218 ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3} time:110520
D/UsbSettings( 2610): [AUTORUN] onStop()
I/chromium( 4730): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/chromium( 4730): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/dalvikvm( 4730): GC_CONCURRENT freed 2682K, 12% free 21970K/24832K, paused 2ms+3ms, total 60ms
D/dalvikvm( 4730): WAIT_FOR_CONCURRENT_GC blocked 52ms
D/dalvikvm( 4730): WAIT_FOR_CONCURRENT_GC blocked 53ms
D/dalvikvm( 4730): GC_FOR_ALLOC freed 339K, 10% free 22362K/24832K, paused 39ms, total 39ms
I/dalvikvm-heap( 4730): Grow heap (frag case) to 24.052MB for 42652-byte allocation
W/PluginManager( 4730): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 42ms. Plugin should use CordovaInterface.getThreadPool().
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4730): GC_FOR_ALLOC freed 105K, 11% free 22368K/24876K, paused 31ms, total 31ms
D/dalvikvm( 4730): GC_FOR_ALLOC freed 125K, 10% free 22389K/24876K, paused 23ms, total 23ms
I/dalvikvm-heap( 4730): Grow heap (frag case) to 24.129MB for 95956-byte allocation
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
D/dalvikvm( 4730): GC_FOR_ALLOC freed 178K, 11% free 22423K/24972K, paused 24ms, total 24ms
I/dalvikvm-heap( 4730): Grow heap (frag case) to 24.208MB for 143930-byte allocation
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4730): GC_FOR_ALLOC freed 254K, 11% free 22471K/25116K, paused 23ms, total 23ms
I/dalvikvm-heap( 4730): Grow heap (frag case) to 24.324MB for 215890-byte allocation
D/dalvikvm( 4730): GC_FOR_ALLOC freed 366K, 11% free 22544K/25328K, paused 23ms, total 24ms
I/dalvikvm-heap( 4730): Grow heap (frag case) to 24.499MB for 323830-byte allocation
D/dalvikvm( 4730): GC_FOR_ALLOC freed 566K, 12% free 22665K/25648K, paused 25ms, total 25ms
I/dalvikvm-heap( 4730): Grow heap (frag case) to 24.770MB for 485740-byte allocation
D/dalvikvm( 4730): GC_FOR_ALLOC freed 862K, 13% free 22841K/26124K, paused 23ms, total 23ms
D/dalvikvm( 4730): GC_FOR_ALLOC freed 1126K, 12% free 23082K/26124K, paused 26ms, total 26ms
D/dalvikvm( 4730): GC_FOR_ALLOC freed 189K, 12% free 23061K/26124K, paused 41ms, total 41ms
I/dalvikvm-heap( 4730): Grow heap (frag case) to 25.736MB for 1092904-byte allocation
,D/dalvikvm( 4730): GC_CONCURRENT freed 1819K, 14% free 23492K/27192K, paused 1ms+2ms, total 33ms
,D/dalvikvm( 4730): GC_FOR_ALLOC freed 210K, 14% free 23400K/27192K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4730): Grow heap (frag case) to 26.588MB for 1639352-byte allocation
,D/dalvikvm( 4730): GC_CONCURRENT freed 1882K, 17% free 24015K/28796K, paused 1ms+3ms, total 35ms
,D/dalvikvm( 4730): GC_FOR_ALLOC freed 1004K, 17% free 23986K/28796K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4730): Grow heap (frag case) to 27.943MB for 2459024-byte allocation
,D/dalvikvm( 4730): GC_CONCURRENT freed 1920K, 21% free 24746K/31200K, paused 1ms+1ms, total 28ms
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,D/dalvikvm( 4730): GC_CONCURRENT freed 2487K, 20% free 25019K/31200K, paused 2ms+6ms, total 36ms
,D/dalvikvm( 4730): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4730): WAIT_FOR_CONCURRENT_GC blocked 23ms
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4730): GC_FOR_ALLOC freed 165K, 21% free 24954K/31200K, paused 37ms, total 39ms
,I/dalvikvm-heap( 4730): Grow heap (frag case) to 30.061MB for 3688532-byte allocation
,D/dalvikvm( 4730): GC_CONCURRENT freed 344K, 19% free 28449K/34804K, paused 2ms+4ms, total 40ms
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.584808 Y: -0.340942 Z: 9.814087 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.584808 .y:-0.340942 .z:9.814087
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.591385 Y: -0.337723 Z: 9.812653 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.591385 .y:-0.337723 .z:9.812653
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/dalvikvm( 4730): GC_FOR_ALLOC freed 4340K, 25% free 26135K/34804K, paused 27ms, total 27ms
,W/jxcore-log( 4730): Initializing JXcore engine
,W/jxcore-log( 4730): JXcore engine is ready
,D/dalvikvm( 4730): GC_CONCURRENT freed 417K, 17% free 28941K/34804K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4730): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 4730): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4730): Starting JXcore engine
,W/jxcore-log( 4730): Platform android
W/jxcore-log( 4730): 
,W/jxcore-log( 4730): Process ARCH arm
W/jxcore-log( 4730): 
,I/jxcore-log( 4730): JXcore Cordova bridge is ready!
I/jxcore-log( 4730): 
,W/jxcore-log( 4730): JXcore engine is started
,E/jxcore  ( 4730): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4730): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4730): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
V/ActivityManager(  962): Finishing activity token=Token{44371cc0 ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3}} r=, result=0, data=null, reason=app-request
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3 f}
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  962): GC_FOR_ALLOC freed 1064K, 51% free 29587K/59836K, paused 75ms, total 75ms
,W/PluginManager( 4730): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 87ms. Plugin should use CordovaInterface.getThreadPool().
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3 f} (pause complete)
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{433443d8 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  962): moveHomeStack:
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1} (in existing)
D/ActivityManager(  962): resumeTopActivityLocked: Resumed ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  962): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,D/PhoneApp( 1447): getIsInUseVoLTE : false
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
,D/WeatherAncestor( 1839): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:53:27
,D/UpdateThreadPoolManager( 1839): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1839): 2 : quick cover state : opened : 0
D/WeatherService( 1839): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1839): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1839): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1839): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherService( 1839): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1839): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:53:27
,D/WeatherService( 1839): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1839): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1839): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1839): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1839): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherService( 1839): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1839): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 1839): 2 : This is isUpdating : false
D/WeatherService( 1839): 2 : requestRefreshAppWidget, isUpdating : false
,D/WeatherAncestor( 1839): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1839): 2 : Map key string is -2
,D/lim     ( 1839): 2 : time = 13:53
I/WeatherReflect( 1839): Model Name : LG-D802
,D/WeatherTheme( 1839): 2 : Different view - status_min_formatted : 51 != 53
D/WeatherTheme( 1839): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1839): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
,D/WeatherTheme( 1839): 2 : Fixed theme : optimus
,D/WeatherTheme( 1839): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,D/WeatherQuickCover( 1839): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1839): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 1839): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1839): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/InputMethodManagerService(  962): IME STATUS OFF
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,W/IInputConnectionWrapper( 4730): showStatusIcon on inactive InputConnection
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/dalvikvm( 1140): GC_FOR_ALLOC freed 6344K, 10% free 71432K/78504K, paused 28ms, total 28ms
,D/dalvikvm( 1488): GC_CONCURRENT freed 5525K, 9% free 60930K/66652K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
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
,D/dalvikvm( 1488): GC_FOR_ALLOC freed 4872K, 9% free 61907K/67448K, paused 17ms, total 17ms
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@4285ef08 time:113579
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/UsbSettings( 2610): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2610): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2610): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2610): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{42b55290 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1} time:113634
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3 f}
I/ActivityManager(  962): Killing 4189:com.google.android.talk/u0a77 (adj 15): empty #17
,V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,E/libEGL  ( 4730): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{43b30c50 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1}
,I/GAV2    ( 4662): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/ConfigService( 1526): onDestroy
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiStateMachine(  962): handleMessage: X
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,E/ThermalEngine(  291): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 4270): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4270): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/WifiController(  962): battery changed pluggedType: 2
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.576141 Y: -0.331253 Z: 9.801208 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.576141 .y:-0.331253 .z:9.801208
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.579636 Y: -0.324005 Z: 9.806931 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.579636 .y:-0.324005 .z:9.806931
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 282 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1219): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 281 plugged : true isCharging : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8104 usec
,D/qcom_sensors_hal(  962): hal_acquire_resources
,I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.569977 Y: -0.325211 Z: 9.824509 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.569977 .y:-0.325211 .z:9.824509
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.576691 Y: -0.335876 Z: 9.829407 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.576691 .y:-0.335876 .z:9.829407
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Sensors (  439): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.573334 Y: -0.334183 Z: 9.816772 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573334 .y:-0.334183 .z:9.816772
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.586273 Y: -0.330582 Z: 9.827866 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.586273 .y:-0.330582 .z:9.827866
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.575745 Y: -0.321976 Z: 9.808640 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.575745 .y:-0.321976 .z:9.808640
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.570007 Y: -0.318878 Z: 9.809601 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.570007 .y:-0.318878 .z:9.809601
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42884b78)
,D/SurfaceFlinger(  274): Screen released, type=0 flinger=0xb787b450
D/qdhwcomposer(  274): hwc_blank: Blanking display: 0
D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
D/KeyguardViewMediator( 1140): handleNotifyScreenOn
D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.580719 Y: -0.328644 Z: 9.825790 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.580719 .y:-0.328644 .z:9.825790
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
I/WindowManager(  962): No lock screen! windowToken=null
,E/SlideAside( 4062): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  962): handleScreenStateChanged: true
,D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2021): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
,D/wpa_supplicant( 2021): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131127
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=132097
D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  962): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2021): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2021): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  962): handleMessage: X
E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
V/SRS_Proc(  277): ParamSet string: screen_state=on
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
V/voice   (  277): voice_set_parameters: enter: screen_state=on
,V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{433495d0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1839): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:53:52
,I/SlideAside( 4062): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1839): 2 : This is isUpdating : false
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1839): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:53:52
D/WeatherService( 1839): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/WeatherService( 1839): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1839): 2 : TimeTick Receiver Unregister
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1839): 2 : shouldTimeTickRegistered : false
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
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
,D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/qdhwcomposer(  274): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 401ms
D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
E/BatteryObserver( 1154): usb Uevent not necessary.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985632899, nextTick: 7134, mDrawingTime: 0
D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985632939, nextTick: 7094, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
,D/WeatherService( 1839): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:53:52
,D/WeatherService( 1839): 2 : ACTION screen on
D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/WeatherService( 1839): 2 : shouldTimeTickRegistered : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
D/WeatherService( 1839): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:53:53
,D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1}
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
I/LGImmersionVibrator(  962): Vibrator off
I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
D/WifiStateMachine(  962): handleScreenStateChanged: false
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
V/SRS_Proc(  277): ParamSet string: screen_state=off
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/voice   (  277): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  277): adev_set_parameters: exit with code(-2)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{431664c0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
D/KeyguardViewManager( 1140): onScreenTurnedOff()
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1154): clear
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): handleMessage: X
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
D/WeatherService( 1839): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:53:53
D/WeatherService( 1839): 2 : ACTION screen off
,D/WeatherService( 1839): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:53:53
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
D/NfcService( 1473): NFC-C OFF
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  439): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  291): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985640056, nextTick: 59973, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985640059, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985650797628701; DSPS: 5276445; Offset: 1453985489773306192
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985670798950464; DSPS: 5931849; Offset: 1453985489773285181
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985690800245872; DSPS: 6587251; Offset: 1453985489773298851
,I/EventLogService( 1944): Aggregate from 1453985522368 (log), 1453983889075 (data)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1526): GC_EXPLICIT freed 1318K, 29% free 17824K/24832K, paused 2ms+6ms, total 47ms
,I/VacuumService( 1526): Vacuum at: now=1453985695823 tag=VacuumService
,I/GoogleURLConnFactory( 1526): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1526): No account for auth token provided
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1526): No account for auth token provided
,W/Uploader( 1526): No account for auth token provided
,W/Uploader( 1526):  no longer exists, so no auth token.
,W/Uploader( 1526): No account for auth token provided
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985700038, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985700054, nextTick: 59978, mDrawingTime: 0
,D/wpa_supplicant( 2021): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985710801158364; DSPS: 7242641; Offset: 1453985489773295816
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985730801605805; DSPS: 7898016; Offset: 1453985489773285493
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985750808964079; DSPS: 8553617; Offset: 1453985489773289031
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985760066, nextTick: 59966, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985760067, nextTick: 59966, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985770809901676; DSPS: 9209008; Offset: 1453985489773280583
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985790810352501; DSPS: 9864382; Offset: 1453985489773304162
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985810810804994; DSPS: 10519757; Offset: 1453985489773298891
,D/dalvikvm( 2662): GC_CONCURRENT freed 7775K, 33% free 16866K/24832K, paused 2ms+1ms, total 35ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985820048, nextTick: 59982, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985820054, nextTick: 59978, mDrawingTime: 0
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x4324f508: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1526): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1526): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1526): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1526): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1526): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1526): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1526): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1526): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 4270): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4270): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4270): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4270): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4270): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4270): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4270): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4270): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4270): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4270): isDataSchedulerEnabled():false
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985830818032798; DSPS: 11175354; Offset: 1453985489773294029
,I/LocationManagerService(  962): remove 433310a0
,D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2662): GC_FOR_ALLOC freed 1699K, 32% free 17054K/24832K, paused 21ms, total 23ms
,D/dalvikvm( 2662): GC_CONCURRENT freed 1741K, 31% free 17267K/24832K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 2662): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Mlt MonitorService( 2662): parseLastkmsg to dump
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985850818904613; DSPS: 11830743; Offset: 1453985489773280834
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985870819348617; DSPS: 12486117; Offset: 1453985489773297592
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985880058, nextTick: 59973, mDrawingTime: 1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985880059, nextTick: 59973, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985890823091161; DSPS: 13141600; Offset: 1453985489773286474
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985910824407142; DSPS: 13797003; Offset: 1453985489773290199
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985930825668853; DSPS: 14452404; Offset: 1453985489773300689
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985940037, nextTick: 59990, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453985940044, nextTick: 59988, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985950827083690; DSPS: 15107811; Offset: 1453985489773281200
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985970828382120; DSPS: 15763213; Offset: 1453985489773297892
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453985990829665446; DSPS: 16418615; Offset: 1453985489773299480
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986000038, nextTick: 59975, mDrawingTime: 7
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986000051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986010831052157; DSPS: 17074021; Offset: 1453985489773282382
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986030832342148; DSPS: 17729423; Offset: 1453985489773290635
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986050833630370; DSPS: 18384825; Offset: 1453985489773297119
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986060053, nextTick: 59969, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986060058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986070835003956; DSPS: 19040230; Offset: 1453985489773297414
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986090836300980; DSPS: 19695633; Offset: 1453985489773282182
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986110838219254; DSPS: 20351056; Offset: 1453985489773277848
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986120038, nextTick: 59976, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986120051, nextTick: 59981, mDrawingTime: 0
,I/ActivityManager(  962): Killing 3136:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986130839125028; DSPS: 21006445; Offset: 1453985489773298612
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986150840418458; DSPS: 21661848; Offset: 1453985489773279787
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986170841752981; DSPS: 22317251; Offset: 1453985489773302054
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986180050, nextTick: 59967, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986180058, nextTick: 59974, mDrawingTime: 0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986190843142348; DSPS: 22972657; Offset: 1453985489773287612
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986210844450726; DSPS: 23628060; Offset: 1453985489773283734
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986230845736343; DSPS: 24283462; Offset: 1453985489773287613
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986240053, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986240055, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986250847997638; DSPS: 24938896; Offset: 1453985489773290607
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986270849506901; DSPS: 25594305; Offset: 1453985489773304509
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986290850787935; DSPS: 26249707; Offset: 1453985489773303805
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986300041, nextTick: 59987, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986300045, nextTick: 59986, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986310852216521; DSPS: 26905114; Offset: 1453985489773298064
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986330853062243; DSPS: 27560502; Offset: 1453985489773289294
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986350854368484; DSPS: 28215905; Offset: 1453985489773283279
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986360038, nextTick: 59985, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986360044, nextTick: 59987, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986370855944988; DSPS: 28871316; Offset: 1453985489773303387
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986390857858417; DSPS: 29526739; Offset: 1453985489773294209
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 270 plugged : true isCharging : false
,D/HeadsetStateMachine( 1219): Disconnected process message: 10
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986410859232994; DSPS: 30182144; Offset: 1453985489773295494
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986420039, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986420045, nextTick: 59985, mDrawingTime: 1
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  962): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  962): Done.
,D/QcConnectivityService(  962): Setting timer for 720seconds
,I/ConfigFetchService( 1944): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigService( 1526): onCreate
,I/ConfigFetchService( 1944): running network task: configservice_periodic
,E/WakeLock( 1944): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1944): launchTask
,I/ConfigFetchService( 1944): service connected
,D/ConfigFetchService( 1944): ConfigApi connection successful.
,V/ConfigFetchTask( 1944): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U15CX8Q01s-cwiZRe7noLUw3oBHEV3S7IYbog6z_uEla876yFGEO-C9Ih4z27XFySV-PfuTFvpn8MH69vLeZ7all6rzTFoCo94s6k4_cMrTXbvEV2cmR7YSq2HvIHTeVVItx8dGYYj4opGCreOvxV81mc0g1Zk8YCKjW6tonG11yUNAsvFi3NAtAJqsyH52O1so8nx
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GoogleURLConnFactory( 1944): Using platform SSLCertificateSocketFactory
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1526): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/ConfigFetchTask( 1944): updating config table for com.google.android.gms
,I/ConfigFetchService( 1944): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1944): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1944): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1944): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1944): fetch service done; releasing wakelock
,I/ConfigFetchService( 1944): stopping self
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986430860858976; DSPS: 30837557; Offset: 1453985489773304045
,I/ConfigService( 1526): onDestroy
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986450862232197; DSPS: 31492963; Offset: 1453985489773273457
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986470863531460; DSPS: 32148365; Offset: 1453985489773290982
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986480048, nextTick: 59980, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986480051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986490864922546; DSPS: 32803770; Offset: 1453985489773308777
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986510866248789; DSPS: 33459174; Offset: 1453985489773292247
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986530868163104; DSPS: 34114597; Offset: 1453985489773283954
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986540051, nextTick: 59978, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986540054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986550869894190; DSPS: 34770013; Offset: 1453985489773306056
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986570871171629; DSPS: 35425415; Offset: 1453985489773301756
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986590872514383; DSPS: 36080819; Offset: 1453985489773301737
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986600041, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986600059, nextTick: 59972, mDrawingTime: 1
,D/dalvikvm(  962): GC_CONCURRENT freed 2177K, 49% free 30574K/59836K, paused 21ms+12ms, total 189ms
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986610873940156; DSPS: 36736226; Offset: 1453985489773293184
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986630875212336; DSPS: 37391628; Offset: 1453985489773283626
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986650877281600; DSPS: 38047055; Offset: 1453985489773308212
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986660046, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986660056, nextTick: 59974, mDrawingTime: 1
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Disconnect event
D/wpa_supplicant( 2021): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2021): wlan0: Deauthentication notification
D/wpa_supplicant( 2021): wlan0:  * reason 0
D/wpa_supplicant( 2021): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2021): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2021): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2021): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
D/WifiStateMachine(  962): handleMessage: E msg.what=147460,
D/WifiStateMachine(  962): processMsg: ConnectedState,
D/WifiStateMachine(  962): processMsg: L2ConnectedState,
D/WifiStateMachine(  962): processMsg: ConnectModeState,
D/WifiStateMachine(  962): Network connection lost
D/WifiStateMachine(  962): Stopping DHCP and clearing IP,
,D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true,
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0,
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb81e0d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2021): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...,
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31,
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1',
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1),
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event,
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  962): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/wpa_supplicant( 2021): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2021): wlan0: nl80211: scan request
,D/wpa_supplicant( 2021): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2021): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2021): wlan0: nl80211: Scan trigger
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiNative-wlan0(  962):    returned true
,D/DhcpStateMachine(  962): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  962): addressRemoved: 192.168.1.157/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
D/QCNEA   (  478): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  478): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  478): |CAC| updateNetCfgInfo
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC|                   Netconfig               
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  478): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  478): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  478): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  478): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  478): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  478): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| Received bssid= 
D/QCNEA   (  478): |CAC| net type = 3
V/QCNEA   (  478): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  478): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  478): |CAC| 	ssid           =NG700
V/QCNEA   (  478): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  478): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  478): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  478): |CAC| dispatchNetCfg: updating:0xb76588dc
,D/QCNEA   (  478): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/WifiHS20(  962): hidePasspointNotification off =false
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
,D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
,D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
,D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5959 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
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
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
,D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5959): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5959): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5959): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 5959): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 5959): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5959): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
W/NetworkManagementService(  962): route cmd failed: 
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
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x61f08ba0 clazz=0x80700001 iface=wlan0 mask=0x3
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6002 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  962): Killing 3939:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/NativeCrypto( 1526): Read error: ssl=0x60dcfda8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1526): SSL shutdown failed: ssl=0x60dcfda8: I/O error during system call, Broken pipe
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6002): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6002): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6002): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/DhcpStateMachine(  962): StoppedState
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 6002): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6002): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6002): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6002): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6002): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6002): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6002): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6002): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6002): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 4349:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2021): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2021): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2021): nl80211: Survey data missing
D/wpa_supplicant( 2021): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 4 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: BSS: Add new id 5 BSSID 00:37:b7:9d:3e:73 SSID 'FunBox2-3E72'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2021): wlan0: New scan results available
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2021): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2021): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2021): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2021): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2021): wlan0: 2: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-90 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2021): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2021): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2021): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2021): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81e25a8  current_ssid=0x0
D/wpa_supplicant( 2021): scard is not null..
D/wpa_supplicant( 2021): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:,00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2021): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2021): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2021): RSN: PMKSA cache search - network_ctx=0xb81e25a8 try_opportunistic=0
D/wpa_supplicant( 2021): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2021): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2021): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2021): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2021): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2021): nl80211: Unsubscribe mgmt frames handle 0xb81e1590 (mode change)
D/wpa_supplicant( 2021): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2021): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2021):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021):   * freq=2412
D/wpa_supplicant( 2021):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2021):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021):   * Auth Type 0
D/wpa_supplicant( 2021):   * WPA Versions 0x2
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 00:37:b7:9d:3e:73]
D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedSta,te
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2021): nl80211: Connect request send successfully
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2021): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/Tethering(  962): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
,D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
,D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Connect event
D/wpa_supplicant( 2021): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2021): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2021): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2021): wlan0: Association info event
D/wpa_supplicant( 2021): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2021): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2021): wlan0: freq=2412 MHz
D/wpa_supplicant( 2021): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2021): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): scard is not null..
D/wpa_supplicant( 2021): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2021): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2021): TDLS: Remove peers on association
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2021): EAPOL: enable timer tick
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
,D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 12 94 bc 2b db 0b 99 d9 ae 33 b7 c1 1f fa c5 ...
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): 12 94 bc 2b db 0b 99 d9 ae 33 b7 c1 1f fa c5 1c c4 e1 8a 53 5b df ea 5c 85 89 13 da 6f 2e c9 86
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 12 94 bc 2b db 0b 99 d9 ae 33 b7 c1 1f fa c5 ...
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2021): Get randomness: len=32 entropy=4
D/wpa_supplicant( 2021): WPA: Renewed SNonce - hexdump(len=32): 0d 62 b5 65 11 a6 89 70 14 e3 74 bd 4b e4 54 e1 3b a7 e2 1d 26 33 81 3f d4 87 b0 7f 15 f4 27 94
D/wpa_supplicant( 2021): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): WPA: Nonce1 - hexdump(len=32): 0d 62 b5 65 11 a6 89 70 14 e3 74 bd 4b e4 54 e1 3b a7 e2 1d 26 33 81 3f d4 87 b0 7f 15 f4 27 94
D/wpa_supplicant( 2021): WPA: Nonce2 - hexdump(len=32): 12 94 bc 2b db 0b 99 d9 ae 33 b7 c1 1f fa c5 1c c4 e1 8a 53 5b df ea 5c 85 89 13 da 6f 2e c9 86
D/wpa_supplicant( 2021): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2021): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 8c 14 3c d7 a7 29 80 75 eb b3 d3 52 8a 1b 39 7d
,D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 0d 62 b5 65 11 a6 89 70 14 e3 74 bd 4b e4 54 ...
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 12 94 bc 2b db 0b 99 d9 ae 33 b7 c1 1f fa c5 ...
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): 12 94 bc 2b db 0b 99 d9 ae 33 b7 c1 1f fa c5 1c c4 e1 8a 53 5b df ea 5c 85 89 13 da 6f 2e c9 86
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 97 0f 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): fc 96 2b 56 fb 8f c6 08 c3 da ab 06 13 d2 bc f4
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 12 94 bc 2b db 0b 99 d9 ae 33 b7 c1 1f fa c5 ...
D/wpa_supplicant( 2021): RSN: encrypted key data - hexdump(len=56): 00 84 41 e7 1e 80 ff 00 fd 4e a0 30 91 c4 a2 67 f9 97 35 04 23 f0 65 1c 01 18 0b 0e c2 c7 c6 f9 ...
D/wpa_supplicant( 2021): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 0d bc ...
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): 86 43 29 7b 76 c1 cf b8 d2 f9 24 96 4c ad 23 14
,D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2021): wlan0: WPA: Installing PTK to the driver,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb81e1c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2021): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16),
D/wpa_supplicant( 2021): WPA: RSC - hexdump(len=6): 97 0f 00 00 00 00
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f4803a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2021):    broadcast key,
I/wpa_supplicant( 2021): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2021): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=1,
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2021): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2021): EAPOL authentication completed successfully
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): Network connection established,
,D/WifiNative-wlan0(  962): doString: STATUS
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2021): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
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
,I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
,I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  962): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiStateMachine(  962): handleMessage: X
,I/ActivityManager(  962): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=6052 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-48ms what=147462 obj=android.net.wifi.StateChangeResult@4325ccd8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-46ms what=147462 obj=android.net.wifi.StateChangeResult@4324ef70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-45ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-12ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,D/HyLog   ( 6052): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6052): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6052): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
V/DownloadManager( 6052): DownloadService onCreate
,D/CommandListener(  271): Setting iface cfg
D/WifiStateMachine(  962): addressUpdated: 192.168.1.157/24 on wlan0 flags 128 scope 0
,I/DownloadManager( 6052): in removeSpuriousFiles
,D/CommandListener(  271): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiStateMachine(  962): handleMessage: X
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43264278 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43264278 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.157/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-5ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 6052): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428a0838 on behalf of 6052
I/DownloadManager( 6052): in trimDatabase
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
V/DownloadManager( 6052): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
V/DownloadManager( 6052): DownloadService onStartCommand
V/DownloadManager( 6052): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428a2e00 on behalf of 6052
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428a53c8 on behalf of 6052
,D/eas_req ( 4644): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/WifiStateMachine(  962): DHCP successful
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,E/Parcel  (  478): Reading a NULL string not supported here.
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
,D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/DownloadManager( 6052): DownloadService onDestroy
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  962): handleMessage: X
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
I/LgeMiscReceiver( 4379): networkInfo.isConnected() = false
D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
,D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
W/linker  ( 4644): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4644): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4644): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4644): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4644): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4644): register_HtmlEditor, Success
D/HtmlEditor( 4644): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4644): register_HtmlEditorTimer, Success
D/HtmlEditor( 4644): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4644): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4644): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4644): register_HtmlEditorFont, Success
D/HtmlEditor( 4644): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4644): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4644): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4644): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4644): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4644): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4644): JNI_OnLoad Success
I/HubEmail( 4644): JNI_OnLoad()
I/HubEmail( 4644): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4644): registerNatives()
I/HubEmail( 4644): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4644): registerNativeMethods()
I/HubEmail( 4644): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  962): handleMessage: X
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6073 uid=10052 gids={50052, 3003}
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,V/        (  271): RouteController
,I/ActivityManager(  962): Killing 4566:com.android.defcontainer/u0a4 (adj 15): empty #17
D/HyLog   ( 6073): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6073): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6073): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  271): RouteController
,D/MobileConnectivityChangeReceiver( 6073): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
V/LGRssiData( 6073): [loadRssi] File not exist 
,V/LGRssiData( 6073): [loadRssi] File not exist 
D/MobileConnectivityChangeReceiver( 6073): onReceive CONNECTIVITY_CHANGE networkType=1
,V/TelephonyAutoProfiling( 6073): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 6073): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6073): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6073): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6073): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  271): RouteController
,V/TelephonyAutoProfiling( 6073): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6073): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6073): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6100 uid=10063 gids={50063, 3003, 1028, 1015}
,V/        (  271): RouteController
E/PhoneMonitor( 6073): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6073): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  962): Killing 4601:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/QCNEA   (  478): |CAC| readCallback: read len:492, ret:0, errno:0
,D/QCNEA   (  478): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  478): |CAC| updateNetCfgInfo
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC|                   Netconfig               
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  478): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  478): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  478): |CAC| 	NetConfig: ip4        =192.168.1.157
V/QCNEA   (  478): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  478): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  478): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  478): |CAC| net type = 1
V/QCNEA   (  478): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  478): |CAC| Received ssid= NG700
V/QCNEA   (  478): |CAC| 	ssid           =NG700
V/QCNEA   (  478): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  478): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  478): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  478): |CAC| dispatchNetCfg: updating:0xb76588dc
,D/QCNEA   (  478): |CAC| readCallback: read len:0, ret:-1, errno:11
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6100): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6100): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6100): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1944): Checking schedule, now: 1453986669666 next: 1453985555586
,I/CheckinService( 1944): active receiver: enabled
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinService( 1944): Preparing to send checkin request
,I/EventLogService( 1944): Accumulating logs since 1453985695622
,I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6124 uid=10066 gids={50066, 4002, 3003, 1028}
,E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,D/HyLog   ( 6124): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6124): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6124): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  962): Killing 4630:com.lge.bnr/1000 (adj 15): empty #17
D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6140 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/HyLog   ( 6140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6140): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6140): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 6140): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6162 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  962): Killing 4238:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6162): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6162): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6162): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/NFS     ( 6162): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6162): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6162): intf.getDisplayName() = lo
,I/Wireless_Storage( 6162): intf.getDisplayName() = sit0
I/Wireless_Storage( 6162): intf.getDisplayName() = p2p0
I/Wireless_Storage( 6162): intf.getDisplayName() = teql0
I/Wireless_Storage( 6162): intf.getDisplayName() = wlan0
,D/NFS     ( 6162): interface name:wlan0 name:wlan0
D/NFS     ( 6162): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6162): interface name:wlan0 name:wlan0
D/NFS     ( 6162): addr:192.168.1.157 broadcast:192.168.1.255
,I/Wireless_Storage( 6162): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6183 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 4253:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/dalvikvm(  275): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+3ms, total 23ms
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6183): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6183): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6183): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 1526): GC_CONCURRENT freed 1755K, 28% free 18048K/24832K, paused 4ms+5ms, total 54ms
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 6183): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x431f2170: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6201 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6201): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6201): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6201): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 6201): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6201): VFY: replacing opcode 0x60 at 0x000b
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.157
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  962): RunningState
D/dalvikvm( 6201): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6201): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6201): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 6201): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6201): install
,I/MultiDex( 6201): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6201): loading existing secondary dex files
,I/MultiDex( 6201): load found 3 secondary dex files
,I/MultiDex( 6201): install done
,D/dalvikvm( 6201): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6201): VFY: unable to resolve instance field 61
,D/dalvikvm( 6201): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6201): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6201): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6201): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6201): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6201): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6201): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6201): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6201): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6201): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285db48
D/dalvikvm( 6201): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285db48
,D/dalvikvm( 6201): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285db48, skipping init
,D/dalvikvm( 6201): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285db48
D/dalvikvm( 6201): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285db48
,V/JNIHelp ( 6201): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 6183): Binding Chromium to the main looper Looper (main, tid 1) {42864480}
,I/chromium( 6183): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6183): Initializing chromium process, renderers=0
,W/chromium( 6183): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6183): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6183): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6183): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6183): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6183): Remote Branch: 
I/Adreno-EGL( 6183): Local Patches: 
I/Adreno-EGL( 6183): Reconstruct Branch: 
,D/dalvikvm( 6201): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4285db48
D/dalvikvm( 6201): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4285db48
,D/dalvikvm( 6201): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4285db48
,D/dalvikvm( 6201): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4285db48
,I/NSApplication( 6183): Starting up...
,I/ActivityManager(  962): Killing 4662:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/ProviderInstaller( 6201): Installed default security provider GmsCore_OpenSSL
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/QRemote ( 6002): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6002): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/wpa_supplicant( 2021): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2021): EAPOL: disable timer tick
,D/QRemote ( 6002): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6002): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6002): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6002): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 5959): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5959): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6002): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6002): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6002): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6002): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1526): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1526): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1526): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1944): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/dalvikvm( 6201): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6201): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6201): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6201): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
,W/dalvikvm( 6201): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6201): VFY: replacing opcode 0x6e at 0x0201
,D/WearableService( 1855): callingUid 10006, callindPid: 1855
,E/MDM     ( 1422): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1944): Restart initialization of location
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fb4000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fb4000
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
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=3880838791
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6201): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a48930
,D/dalvikvm( 6201): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a48930
,D/dalvikvm( 6201): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a48930, skipping init
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986670878220967; DSPS: 38702446; Offset: 1453985489773301534
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
,D/WVCdm   (  277): PrepareKeyRequest: nonce=4197415536
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,W/Settings( 6201): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 6201): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6258): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 6201): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6201): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 75ms
,I/Adreno-EGL( 6201): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6201): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6201): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6201): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6201): Remote Branch: 
I/Adreno-EGL( 6201): Local Patches: 
I/Adreno-EGL( 6201): Reconstruct Branch: 
,I/Adreno-EGL( 6201): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6201): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6201): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6201): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6201): Remote Branch: 
I/Adreno-EGL( 6201): Local Patches: 
I/Adreno-EGL( 6201): Reconstruct Branch: 
,I/Adreno-EGL( 6201): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6201): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6201): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6201): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6201): Remote Branch: 
I/Adreno-EGL( 6201): Local Patches: 
I/Adreno-EGL( 6201): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,D/dalvikvm(  962): GC_EXPLICIT freed 2219K, 49% free 30558K/59360K, paused 2ms+7ms, total 96ms
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 1944): GC_CONCURRENT freed 1970K, 22% free 19546K/24832K, paused 5ms+6ms, total 58ms
,D/dalvikvm( 1944): WAIT_FOR_CONCURRENT_GC blocked 41ms
,I/CheckinTask( 1944): Sending checkin request (11460 bytes)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
,D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
,D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
,I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4039): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4039): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4039): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4039): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4039): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6052): DownloadService onCreate
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/eas_req ( 4644): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4379): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6073): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6073): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6140): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6162): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6162): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 6052): in removeSpuriousFiles
V/DownloadManager( 6052): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428ab278 on behalf of 6052
I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 6052): in trimDatabase
V/DownloadManager( 6052): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
V/DownloadManager( 6052): DownloadService onStartCommand
,V/DownloadManager( 6052): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428acc70 on behalf of 6052
D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428aebf8 on behalf of 6052
,I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 6052): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
,D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
,I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6052): DownloadService onCreate
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
I/DownloadManager( 6052): in removeSpuriousFiles
D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6052): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428b34a8 on behalf of 6052
I/DownloadManager( 6052): in trimDatabase
,V/DownloadManager( 6052): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428b4ae8 on behalf of 6052
,V/DownloadManager( 6052): DownloadService onStartCommand
,V/DownloadManager( 6052): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4379): networkInfo.isConnected() = true
D/PhoneState( 4379): setPdpRejectCasuse : false
,W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428b6b48 on behalf of 6052
,D/MobileConnectivityChangeReceiver( 6073): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6073): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 6052): DownloadService onDestroy
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6140): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 6162): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6162): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
,D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
,I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 6052): DownloadService onCreate
,D/EAS     ( 4644): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4379): networkInfo.isConnected() = true
,D/PhoneState( 4379): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6073): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6073): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6140): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 6162): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6162): CONNECT : WIFI_CONNECT
,W/Settings( 4644): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 6052): in removeSpuriousFiles
,V/DownloadManager( 6052): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428bad10 on behalf of 6052
,I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 6052): in trimDatabase
,V/DownloadManager( 6052): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428bbde0 on behalf of 6052
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6052): DownloadService onStartCommand
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 6052): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6052): created cursor android.database.sqlite.SQLiteCursor@428be8b8 on behalf of 6052
I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
,V/DownloadManager( 6052): DownloadService onDestroy
E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x433f25f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,I/CheckinTask( 1944): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1944): Checking schedule, now: 1453986674172 next: 1454564070169
,I/CheckinService( 1944): active receiver: disabled
,I/CheckinService( 1944): Checking schedule, now: 1453986674221 next: 1454564070169
,I/CheckinService( 1944): active receiver: disabled
,D/GCM     ( 1526): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1526): Connected
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1526): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/GAV2    ( 6183): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ActivityManager(  962): Killing 5959:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): Killing 4270:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 4062): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4062): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  962): Handling package changes for user 0
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=6363 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 6363): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6363): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6363): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  962): applying state to connected service
,I/MediaCodecList( 6363): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,D/LocationProviderProxy(  962): applying state to connected service
I/MediaCodecList( 6363): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 6363): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/Babel   ( 6363): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6363): MmsConfig.loadMmsSettings
,I/MediaCodecList( 6363): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 6363): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 6363): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 6363): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6363): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6363): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6363): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 6363): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6363): MmsConfig.loadFromResources
,E/Babel   ( 6363): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6363): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 6363): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4039): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4039): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4039): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
V/LGRssiData( 6363): [loadRssi] File not exist 
,V/LGRssiData( 6363): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6363): [loadFeatureFromXml] *** start feature loading from xml
,D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
,V/TelephonyAutoProfiling( 6363): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 6363): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 6363): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
,D/AppUp4:Utils( 4039): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4039): Event For Nothing, skip.
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6414 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 6414): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6414): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6414): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 6414): BUILD Country: EU
,I/SystemConfig( 6414): BUILD Operator: OPEN
I/ActivityManager(  962): Killing 6002:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6428 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,I/SystemConfig( 6414): systemFeature RCS result false
,D/SystemConfig( 6414): refreshRcsSupport() :false
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  962): Killing 6052:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/HyLog   ( 6428): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6428): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6428): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/IcingCorporaProvider( 2679): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  962): Killing 4644:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6444 uid=10050 gids={50050, 3003, 1028, 1015}
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  962): GC_EXPLICIT freed 2343K, 49% free 30658K/59360K, paused 5ms+14ms, total 169ms
,D/HyLog   ( 6444): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6444): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6444): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6444): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 6444): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 6444): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6444): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 6444): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 6444): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6444): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6444): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6444): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 6444): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/IcingCorporaProvider( 2679): UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,W/Settings( 6444): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6444): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6444): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6444): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 6444): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6444): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 6444): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6444): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  962): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6482 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/dalvikvm( 6444): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 6444): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x001a
,D/HyLog   ( 6482): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6482): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6482): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 6444): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 6444): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6444): VFY: replacing opcode 0x6e at 0x0049
,D/Finsky  ( 6444): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6444): [1] 2.run: Finished loading 1 libraries.
,D/PackageBroadcastService( 1944): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1944): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1944): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 6482): DownloadService onCreate
,I/DownloadManager( 6482): in removeSpuriousFiles
,V/DownloadManager( 6482): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6482): DownloadService onStartCommand
V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428a46c8 on behalf of 6444
,V/DownloadManager( 6482): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6482): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428a5fb8 on behalf of 6482
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428a8010 on behalf of 6482
,I/DownloadManager( 6482): in trimDatabase
,V/DownloadManager( 6482): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428aa290 on behalf of 6482
,D/Finsky  ( 6444): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 6482): DownloadService onDestroy
I/ActivityManager(  962): Killing 6073:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/Finsky  ( 6444): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6444): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 6444): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6444): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6444): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6444): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6444): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 6444): Total arena pages for JIT: 11
,I/dalvikvm( 6444): Total arena pages for JIT: 12
I/dalvikvm( 6444): Total arena pages for JIT: 13
,I/dalvikvm( 6444): Total arena pages for JIT: 14
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1526): GC_EXPLICIT freed 1366K, 28% free 18014K/24832K, paused 3ms+7ms, total 59ms
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 6444): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6444): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6444): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6444): [1] DailyHygiene.reschedule: Scheduling new run in 88 minutes (failures=3),
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 6363): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 6100:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986690879140752; DSPS: 39357836; Offset: 1453985489773305792
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 6444): [471] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6444): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986710880480692; DSPS: 40013240; Offset: 1453985489773302958
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986720051, nextTick: 59975, mDrawingTime: 5
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986720058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986730881947246; DSPS: 40668648; Offset: 1453985489773304668
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986750883224582; DSPS: 41324050; Offset: 1453985489773300266
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986770884487856; DSPS: 41979452; Offset: 1453985489773281802
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986780050, nextTick: 59978, mDrawingTime: 3
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1453986780057, nextTick: 59973, mDrawingTime: 1
,D/dalvikvm( 2662): GC_CONCURRENT freed 2446K, 33% free 16741K/24832K, paused 2ms+3ms, total 37ms
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Disconnect event
D/wpa_supplicant( 2021): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2021): wlan0: Deauthentication notification
D/wpa_supplicant( 2021): wlan0:  * reason 0
D/wpa_supplicant( 2021): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Auto connect enabled: try to reconnect (wps=0 wpa_state=9)
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 500000 usec
D/wpa_supplicant( 2021): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 2021): wlan0: Blacklist count 1 --> request scan in 100 ms
D/wpa_supplicant( 2021): wlan0: Setting scan request: 0 sec 100000 usec
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2021): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0],
,D/WifiStateMachine(  962): handleMessage: E msg.what=147460,
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb81e0d6c key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2021): wlan0: State: COMPLETED -> DISCONNECTED,
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0,
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state INITIALIZE,
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP]),
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event,
,D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): Network connection lost
D/WifiStateMachine(  962): Stopping DHCP and clearing IP
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
,D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  962): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): addressRemoved: 192.168.1.157/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/wpa_supplicant( 2021): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2021): wlan0: nl80211: scan request
,D/wpa_supplicant( 2021): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/wpa_supplicant( 2021): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 2021): wlan0: nl80211: Scan trigger
D/WifiHS20(  962): hidePasspointNotification off =false
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
D/QCNEA   (  478): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  478): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  478): |CAC| updateNetCfgInfo
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC|                   Netconfig               
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  478): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  478): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  478): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  478): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  478): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  478): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| Received bssid= 
D/QCNEA   (  478): |CAC| net type = 3
V/QCNEA   (  478): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  478): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  478): |CAC| 	ssid           =NG700
V/QCNEA   (  478): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  478): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  478): |CAC| dispatching netcfgupdate for wlan
,D/QCNEA   (  478): |CAC| dispatchNetCfg: updating:0xb76588dc
,D/QCNEA   (  478): |CAC| readCallback: read len:0, ret:-1, errno:11,
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
,V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 0
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
,I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6631 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiStateMachine(  962): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  962): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
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
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '66 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 66 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '67 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 67 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '68 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 68 Failed to remove route from default table (No such process)'
V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 6631): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6631): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6631): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  271): RouteController
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  271): RouteController
,V/        (  271): RouteController
,I/PCSuite ( 6631): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/        (  271): RouteController
,W/NetworkManagementService(  962): route cmd failed: 
W/NetworkManagementService(  962): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route del src v6 2' failed with '400 70 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x61f08ba0 clazz=0xc6800001 iface=wlan0 mask=0x3
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
,V/NativeCrypto( 1526): Read error: ssl=0x644a08a8: I/O error during system call, Connection timed out
,D/PCSuite ( 6631): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6631): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/NativeCrypto( 1526): SSL shutdown failed: ssl=0x644a08a8: I/O error during system call, Broken pipe
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6674 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  962): Killing 6124:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/DhcpStateMachine(  962): StoppedState
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/HyLog   ( 6674): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6674): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6674): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/QRemote ( 6674): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6674): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 6674): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6674): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6674): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6674): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6674): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6674): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6674): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  962): Killing 6140:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2021): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2021): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2021): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 2021): nl80211: Survey data missing
D/wpa_supplicant( 2021): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 2021): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 2021): wlan0: New scan results available
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2021): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2021): WPS: AP 00:37:b7:9d:3e:73 type 0 added
D/wpa_supplicant( 2021): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
D/wpa_supplicant( 2021): WPS: AP[2] 00:37:b7:9d:3e:73 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2021): wlan0:    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 2021): wlan0: 2: 00:37:b7:9d:3e:73 ssid='FunBox2-3E72' wpa_ie_len=26 rsn_ie_len=24 caps=0x111 level=-91 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: No APs found - clear blacklist and try again
D/wpa_supplicant( 2021): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
D/wpa_supplicant( 2021): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2021): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-57 wps
D/wpa_supplicant( 2021): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2021): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-59 wps
D/wpa_supplicant( 2021): wlan0:    selected based on RSN IE
,D/wpa_supplicant( 2021): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700',
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2021): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2021): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81e25a8  current_ssid=0x0
D/wpa_supplicant( 2021): scard is not null..
D/wpa_supplicant( 2021): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2021): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 2021): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01,
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
,D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00,
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2021): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2021): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 2021): wlan0: Cancelling scan request
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0),
,D/wpa_supplicant( 2021): wlan0: WPA: clearing own WPA/RSN IE,
,D/wpa_supplicant( 2021): wlan0: Automatic auth_alg selection: 0x1
,D/wpa_supplicant( 2021): RSN: PMKSA cache search - network_ctx=0xb81e25a8 try_opportunistic=0,
,D/wpa_supplicant( 2021): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2021): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2021): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2021): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE
,D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: WPA: using GTK CCMP,
D/wpa_supplicant( 2021): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2021): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2021): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
,D/wpa_supplicant( 2021): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE,
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2021): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 2021): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2021): nl80211: Unsubscribe mgmt frames handle 0xb81e1590 (mode change)
D/WifiStateMachine(  962): handleMessage: E msg.what=147461
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState,
D/WifiStateMachine(  962): processMsg: DriverStartedState,
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  962): doString: BSS RANGE=0- MASK=0x21987
D/WifiMonitor(  962): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,W/WifiMonitor(  962): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
D/wpa_supplicant( 2021): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590,
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0c,
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590,
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09,
,D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 07,
D/wpa_supplicant( 2021): nl80211: Register frame type=0xd0 nl_handle=0xb81e1590
D/wpa_supplicant( 2021): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2021): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2021):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021):   * freq=2412,
D/wpa_supplicant( 2021):   * SSID - hexdump(len=5): 4e 47 37 30 30,
,D/wpa_supplicant( 2021):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021):   * Auth Type 0
,D/wpa_supplicant( 2021):   * WPA Versions 0x2
D/wpa_supplicant( 2021): nl80211: Connect request send successfully
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2021): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987',
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/wpa_supplicant( 2021): nl80211: Event message available
D/wpa_supplicant( 2021): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2021): nl80211: Connect event
D/wpa_supplicant( 2021): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2021): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2021): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2021): wlan0: Association info event
D/wpa_supplicant( 2021): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2021): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2021): wlan0: freq=2412 MHz
D/wpa_supplicant( 2021): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2021): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2021): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2021): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): scard is not null..
D/wpa_supplicant( 2021): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2021): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2021): TDLS: Remove peers on association
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2021): EAPOL: enable timer tick
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: Cancelling scan request
,D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added,
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700],
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiMonitor(  962): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  962): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48,
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c8 79 f2 f8 c4 5b e1 f3 f1 38 1d fe 5e 07 ee ...
D/wpa_supplicant( 2021): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): c8 79 f2 f8 c4 5b e1 f3 f1 38 1d fe 5e 07 ee ec 07 fc 1e 04 ea a5 7d f6 e3 83 83 54 70 79 23 0b
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 c8 79 f2 f8 c4 5b e1 f3 f1 38 1d fe 5e 07 ee ...
D/wpa_supplicant( 2021): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 2021): Get randomness: len=32 entropy=4
,D/wpa_supplicant( 2021): WPA: Renewed SNonce - hexdump(len=32): 81 1f d1 7b 7e d5 7b e5 14 38 ba 2d 17 f4 00 00 75 f6 d3 1f f6 15 f2 bd b3 e7 0f d7 d2 c6 36 d4
D/wpa_supplicant( 2021): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): WPA: Nonce1 - hexdump(len=32): 81 1f d1 7b 7e d5 7b e5 14 38 ba 2d 17 f4 00 00 75 f6 d3 1f f6 15 f2 bd b3 e7 0f d7 d2 c6 36 d4
D/wpa_supplicant( 2021): WPA: Nonce2 - hexdump(len=32): c8 79 f2 f8 c4 5b e1 f3 f1 38 1d fe 5e 07 ee ec 07 fc 1e 04 ea a5 7d f6 e3 83 83 54 70 79 23 0b
D/wpa_supplicant( 2021): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2021): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): c9 ec e5 e6 ee 27 3b 63 a6 49 ef 85 44 65 9d 90
,D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 81 1f d1 7b 7e d5 7b e5 14 38 ba 2d 17 f4 00 ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
,D/WifiStateMachine(  962): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/wpa_supplicant( 2021): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c8 79 f2 f8 c4 5b e1 f3 f1 38 1d fe 5e 07 ee ...
D/wpa_supplicant( 2021): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2021): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2021): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2021): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2021):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2021):   key_nonce - hexdump(len=32): c8 79 f2 f8 c4 5b e1 f3 f1 38 1d fe 5e 07 ee ec 07 fc 1e 04 ea a5 7d f6 e3 83 83 54 70 79 23 0b
D/wpa_supplicant( 2021):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_rsc - hexdump(len=8): 07 10 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2021):   key_mic - hexdump(len=16): 87 b3 23 b6 af dd 0c 82 ac bc e1 13 ba 22 86 df
D/wpa_supplicant( 2021): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 c8 79 f2 f8 c4 5b e1 f3 f1 38 1d fe 5e 07 ee ...
D/wpa_supplicant( 2021): RSN: encrypted key data - hexdump(len=56): 32 9b 0a c3 30 a1 60 c4 c2 76 71 dd d2 27 a7 67 b9 23 e1 d4 05 37 c6 bb 69 12 60 23 50 3d fc 2f ...
D/wpa_supplicant( 2021): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2021): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2021): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 0d bc ...
D/wpa_supplicant( 2021): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2021): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2021): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): WPA: Derived Key MIC - hexdump(len=16): f4 a0 9c 5a 34 92 6a a2 ae 66 e2 a5 42 8b 2c d1
D/wpa_supplicant( 2021): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2021): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb81e1c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 2021):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2021): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2021): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2021): WPA: RSC - hexdump(len=6): 07 10 00 00 00 00
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f4803a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 2021):    broadcast key
,I/wpa_supplicant( 2021): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2021): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2021): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2021): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 2021): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2021): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2021): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2021): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2021): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2021): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2021): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2021): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2021): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2021): EAPOL authentication completed successfully
D/wpa_supplicant( 2021): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2021): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2021): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): handleMessage: X
,W/WifiMonitor(  962): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
,D/WifiStateMachine(  962): processMsg: DisconnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
,D/WifiStateMachine(  962): Network connection established
,D/WifiNative-wlan0(  962): doString: STATUS
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2021): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2021): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
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
,I/WifiServiceExtension(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  962): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine(  962): transitionTo: destState=ObtainingIpState
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  478): Reading a NULL string not supported here.
,E/Parcel  (  478): Reading a NULL string not supported here.
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  962): invokeExitMethods: DisconnectedState
,D/WifiStateMachine(  962): moveTempStackToStateStack: i=1,j=5
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
,D/WifiStateMachine(  962): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  962): invokeEnterMethods: ObtainingIpState
,D/DhcpStateMachine(  962): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
,D/WifiStateMachine(  962): processMsg: ObtainingIpState
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  962): ObtainingIpState{ when=-43ms what=147462 obj=android.net.wifi.StateChangeResult@44c1cf68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-39ms what=147462 obj=android.net.wifi.StateChangeResult@44bdc640 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=147459
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-39ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196612
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :false
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
I/AppUp4:CustModeStarterReceiver( 4039): onReceive
D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4039): isOpenOperator : true
D/AppUp4:CustFacade( 4039): isPhone : true
I/LicenseContentProvider( 2735): start selecting data
D/SIMObserver( 2735): simInfo1
I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity
,I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6724 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,D/HyLog   ( 6724): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6724): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6724): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 30
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
,D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 0
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  962):    returned null
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,I/LGEmail ( 6724): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/CommandListener(  271): Setting iface cfg
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
,D/CommandListener(  271): Trying to bring up wlan0
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43264278 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43264278 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): addressUpdated: 192.168.1.157/24 on wlan0 flags 128 scope 0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-5ms what=131212 obj=192.168.1.157/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=196613
D/WifiStateMachine(  962): processMsg: ObtainingIpState
D/WifiStateMachine(  962): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  962): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2021): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2021): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2021): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2021): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2021): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 2021): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
D/WifiStateMachine(  962): DHCP successful
D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  962): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState enter
D/WifiStateMachine(  962): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/LGEmail ( 6724): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/WifiStateTracker(  962): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  962): 
W/WifiStateTracker(  962):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  962):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  962): handleMessage: E msg.what=135190
D/WifiStateMachine(  962): processMsg: VerifyingLinkState
D/WifiStateMachine(  962): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  962): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  962): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): CaptivePortalCheckState enter
D/WifiStateMachine(  962): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
E/Parcel  (  478): Reading a NULL string not supported here.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  962): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
,E/Parcel  (  478): Reading a NULL string not supported here.
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  962): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131092
D/WifiStateMachine(  962): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  962): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  962): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/WifiStateMachine(  962): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/QcConnectivityService(  962): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  962): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  962): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  478): Reading a NULL string not supported here.
E/Parcel  (  478): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/Parcel  (  478): Reading a NULL string not supported here.
E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  962): handleConnectivityChange: preConnState=2 connState=1
,I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,V/        (  271): RouteController
,W/BaseRuntimeLoader( 6724): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6724): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6724): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 6724): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/        (  271): RouteController
,D/EAS     ( 6724): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6724): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,V/        (  271): RouteController
,D/eas_req ( 6724): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4379): networkInfo.isConnected() = false
,V/        (  271): RouteController
,V/        (  271): RouteController
,W/linker  ( 6724): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 6724): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 6724): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 6724): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 6724): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,D/HtmlEditor( 6724): register_HtmlEditor, Success
D/HtmlEditor( 6724): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 6724): register_HtmlEditorTimer, Success
,D/HtmlEditor( 6724): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 6724): register_HtmlEditorDownloader, Success
D/HtmlEditor( 6724): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6724): register_HtmlEditorFont, Success
,D/HtmlEditor( 6724): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6724): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 6724): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6724): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 6724): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 6724): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 6724): JNI_OnLoad Success
,V/        (  271): RouteController
I/HubEmail( 6724): JNI_OnLoad()
I/HubEmail( 6724): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNatives()
I/HubEmail( 6724): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6724): registerNativeMethods()
,I/HubEmail( 6724): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=6757 uid=10052 gids={50052, 3003}
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/QCNEA   (  478): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  478): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  478): |CAC| updateNetCfgInfo
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC|                   Netconfig               
V/QCNEA   (  478): |CAC| *********************************************
V/QCNEA   (  478): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  478): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  478): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  478): |CAC| 	NetConfig: ip4        =192.168.1.157
V/QCNEA   (  478): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  478): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  478): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  478): |CAC| net type = 1
V/QCNEA   (  478): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  478): |CAC| Received ssid= NG700
V/QCNEA   (  478): |CAC| 	ssid           =NG700
D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
V/QCNEA   (  478): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  478): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  478): |CAC| *********************************************
D/QCNEA   (  478): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  478): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  478): |CAC| dispatchNetCfg: updating:0xb76588dc
D/QCNEA   (  478): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/ActivityManager(  962): Killing 6162:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,D/HyLog   ( 6757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6757): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/DhcpStateMachine(  962): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/LGRssiData( 6757): [loadRssi] File not exist 
V/LGRssiData( 6757): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 6757): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 6757): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6757): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 6757): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/BaseRuntimeLoader( 6757): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,D/MobileConnectivityChangeReceiver( 6757): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 6757): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 6757): [getMatchedProfile] selected file : /cust/config/featureset.xml
,V/TelephonyAutoProfiling( 6757): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 6757): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6774 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 6183:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
,E/PhoneMonitor( 6757): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 6757): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+2ms, total 20ms
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,I/CheckinService( 1944): Checking schedule, now: 1453986789207 next: 1453986704169
,I/CheckinService( 1944): active receiver: enabled
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,D/HyLog   ( 6774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6774): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/CheckinService( 1944): Preparing to send checkin request
,I/EventLogService( 1944): Accumulating logs since 1453986669695
,D/dalvikvm(  962): GC_EXPLICIT freed 2021K, 49% free 30617K/59360K, paused 8ms+7ms, total 159ms
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6794 uid=10066 gids={50066, 4002, 3003, 1028}
,D/HyLog   ( 6794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6794): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6794): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  962): Killing 4730:com.test.thalitest/u0a304 (adj 15): empty #17
,D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=6807 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6807): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6807): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6807): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 6807): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6807): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=6821 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  962): Killing 6201:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,D/HyLog   ( 6821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6821): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NFS     ( 6821): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,I/Wireless_Storage( 6821): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 6821): intf.getDisplayName() = lo
I/Wireless_Storage( 6821): intf.getDisplayName() = sit0
,I/Wireless_Storage( 6821): intf.getDisplayName() = p2p0
,I/Wireless_Storage( 6821): intf.getDisplayName() = teql0
I/Wireless_Storage( 6821): intf.getDisplayName() = wlan0
,D/NFS     ( 6821): interface name:wlan0 name:wlan0
D/NFS     ( 6821): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 6821): interface name:wlan0 name:wlan0
,D/NFS     ( 6821): addr:192.168.1.157 broadcast:192.168.1.255
,I/Wireless_Storage( 6821): CONNECT : WIFI_CONNECT
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6833 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 6363:com.google.android.talk/u0a77 (adj 15): empty #17
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x4327c188: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 6833): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 6833): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6833): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6845 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 6845): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6845): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6845): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 6833): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 6845): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 6845): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 6845): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6845): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6845): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 6845): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 6845): install
,I/MultiDex( 6845): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 6845): loading existing secondary dex files
,I/MultiDex( 6845): load found 3 secondary dex files
,I/MultiDex( 6845): install done
,D/dalvikvm( 6845): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6845): VFY: unable to resolve instance field 61
,D/dalvikvm( 6845): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 6845): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6845): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6845): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 6845): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6845): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6845): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6845): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6845): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 6845): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428646b0
D/dalvikvm( 6845): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428646b0
,D/dalvikvm( 6845): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428646b0, skipping init
,D/dalvikvm( 6845): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428646b0
D/dalvikvm( 6845): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428646b0
,V/JNIHelp ( 6845): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/wpa_supplicant( 2021): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2021): EAPOL: disable timer tick
,D/dalvikvm( 6845): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428646b0
,D/dalvikvm( 6845): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428646b0
D/dalvikvm( 6845): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428646b0
,D/dalvikvm( 6845): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428646b0
,V/WebViewChromium( 6833): Binding Chromium to the main looper Looper (main, tid 1) {4285ab98}
,I/chromium( 6833): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6833): Initializing chromium process, renderers=0
,I/ProviderInstaller( 6845): Installed default security provider GmsCore_OpenSSL
,W/chromium( 6833): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 6833): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6833): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6833): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6833): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6833): Remote Branch: 
I/Adreno-EGL( 6833): Local Patches: 
I/Adreno-EGL( 6833): Reconstruct Branch: 
,I/dalvikvm( 6845): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 6845): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6845): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6845): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 6845): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6845): VFY: replacing opcode 0x6e at 0x0201
,I/NSApplication( 6833): Starting up...
,I/ActivityManager(  962): Killing 6414:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  277): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fb4000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fb4000
,D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  962): NetTransition Wakelock for ConnectedState released by timeout
,D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
I/ActivityManager(  962): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=6883 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/HyLog   ( 6883): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6883): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6883): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=386960131
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 6883): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42864c10
,D/dalvikvm( 6883): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42864c10
,D/jxcore_app_log( 6883): JniHelper::setJavaVM(0x41726838), pthread_self() = 1074348372
,E/JX-Cordova( 6883): JXcore wasn't initialized yet
,D/QRemote ( 6674): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6674): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6674): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6674): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 6674): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6674): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 6631): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6631): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 6674): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6674): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 6674): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6674): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1526): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  962): Killing 6428:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1526): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1526): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1944): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/WearableService( 1855): callingUid 10006, callindPid: 1855
,D/dalvikvm( 6845): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a22468
D/dalvikvm( 6845): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a22468
,D/dalvikvm( 6845): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a22468, skipping init
,E/MDM     ( 1422): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1944): Restart initialization of location
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ProcessCpuTracker(  962): Skipping unknown process pid 6709
,W/ProcessCpuTracker(  962): Skipping unknown process pid 6712
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986790885107588; DSPS: 42634832; Offset: 1453985489773291182
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  277): PrepareKeyRequest: nonce=3628458870
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  962): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): handleMessage: E msg.what=131212
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
,D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.157/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  962): handleMessage: X
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  962): send additional Connectivity Action
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  962): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/QcConnectivityService(  962): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  962):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  962): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  962): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/DhcpStateMachine(  962): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.157
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  962): RunningState
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,W/Settings( 6845): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 6845): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 6933): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/dalvikvm( 6845): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 6845): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 79ms
,I/Adreno-EGL( 6845): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6845): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6845): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6845): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6845): Remote Branch: 
I/Adreno-EGL( 6845): Local Patches: 
I/Adreno-EGL( 6845): Reconstruct Branch: 
,I/Adreno-EGL( 6845): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6845): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6845): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6845): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6845): Remote Branch: 
I/Adreno-EGL( 6845): Local Patches: 
I/Adreno-EGL( 6845): Reconstruct Branch: 
,I/Adreno-EGL( 6845): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6845): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 6845): Build Date: 01/20/14 Mon
I/Adreno-EGL( 6845): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 6845): Remote Branch: 
I/Adreno-EGL( 6845): Local Patches: 
I/Adreno-EGL( 6845): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1944): Sending checkin request (11460 bytes)
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
,D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
,D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4039): begin check event
I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4039): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4039): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4039): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4039): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4039): handleAsyncCustNotification do not startCustService
,D/EAS     ( 6724): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6724): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6482): DownloadService onCreate
,D/eas_req ( 6724): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4379): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6757): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6757): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 6807): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/DownloadManager( 6482): in removeSpuriousFiles
,V/DownloadManager( 6482): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428b0a48 on behalf of 6482
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 6807): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/DownloadManager( 6482): in trimDatabase
V/DownloadManager( 6482): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/NFS     ( 6821): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6821): CONNECT : WIFI_CONNECT
W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428b1c80 on behalf of 6482
,V/DownloadManager( 6482): DownloadService onStartCommand
,V/DownloadManager( 6482): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428b4608 on behalf of 6482
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6482): DownloadService onDestroy
,I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 1944): GC_CONCURRENT freed 1861K, 21% free 19648K/24832K, paused 18ms+4ms, total 110ms
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
,I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 6482): DownloadService onCreate
,I/DownloadManager( 6482): in removeSpuriousFiles
,V/DownloadManager( 6482): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428b90e0 on behalf of 6482
D/EAS     ( 6724): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
V/DownloadManager( 6482): DownloadService onStartCommand
V/DownloadManager( 6482): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 6724): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428bb2d0 on behalf of 6482
,I/DownloadManager( 6482): in trimDatabase
I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 6482): DownloadService onDestroy
I/LgeMiscReceiver( 4379): networkInfo.isConnected() = true
D/PhoneState( 4379): setPdpRejectCasuse : false
,V/DownloadManager( 6482): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428bce10 on behalf of 6482
D/MobileConnectivityChangeReceiver( 6757): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6757): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 6807): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 6821): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 6821): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,W/ContextImpl( 6807): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1944): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1944): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  962): GC_EXPLICIT freed 1372K, 49% free 30635K/59360K, paused 4ms+12ms, total 156ms
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x4322a958: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1944): awaiting user notification for token
,I/CheckinRequestBuilder( 1944): Classify the device as Phone.
,I/CheckinTask( 1944): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1944): Checking schedule, now: 1453986793740 next: 1454564189736
,I/CheckinService( 1944): active receiver: disabled
,I/CheckinService( 1944): Checking schedule, now: 1453986793765 next: 1454564189736
,I/CheckinService( 1944): active receiver: disabled
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GCM     ( 1526): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  962): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4039): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
,D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
,D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4039): isOpenOperator : true
,D/AppUp4:CustFacade( 4039): isPhone : true
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4039): begin check event
,I/AppUp4:CustModeStarterReceiver( 4039): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/WifiServiceExtension(  962): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  962): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,V/DownloadManager( 6482): DownloadService onCreate
,D/EAS     ( 6724): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 6724): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4379): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4379): networkInfo.isConnected() = true
,D/PhoneState( 4379): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 6757): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6757): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/DownloadManager( 6482): in removeSpuriousFiles
,V/DownloadManager( 6482): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2932): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/GCM     ( 1526): Connected
,V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428c0538 on behalf of 6482
,D/LGDMSGCM( 6807): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 6724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ContextImpl( 6807): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2932): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/DownloadManager( 6482): in trimDatabase
V/DownloadManager( 6482): DownloadService onStartCommand
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
V/DownloadManager( 6482): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6482): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/NFS     ( 6821): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 6821): CONNECT : WIFI_CONNECT
V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428c32a0 on behalf of 6482
I/LGDMClient( 2932): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 6482): created cursor android.database.sqlite.SQLiteCursor@428c4068 on behalf of 6482
,E/LGDMClient( 2932): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2932): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2932): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 6482): DownloadService onDestroy
,I/LGDMClient( 2932): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1526): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV2    ( 6833): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  962): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ActivityManager(  962): Killing 6631:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  962): Killing 6444:com.android.vending/u0a50 (adj 15): empty #18
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 4062): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 4062): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,D/administrator(  962): Handling package changes for user 0
,I/[LGHome]Launcher( 1488): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=7040 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
,D/HyLog   ( 7040): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7040): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7040): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  962):   Scheme: "mmsto"
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Babel   ( 7040): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 7040): MmsConfig.loadMmsSettings
,I/Babel   ( 7040): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 7040): MmsConfig.loadFromDatabase
,I/MediaCodecList( 7040): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 7040): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 7040): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 7040): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 7040): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7040): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7040): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7040): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 7040): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7040): MmsConfig.loadFromResources
,E/Babel   ( 7040): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7040): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 7040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 7040): [loadRssi] File not exist 
V/LGRssiData( 7040): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 7040): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 7040): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 7040): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 7040): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 4039): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4039): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4039): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4039): onReceive
,D/LocationProviderProxy(  962): applying state to connected service
D/AppUp4:CustFacade( 4039): Context : android.app.ReceiverRestrictedContext@428784b8
D/AppUp4:CustFacade( 4039): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4039): isOpenOperator : true
D/LocationProviderProxy(  962): applying state to connected service
,D/AppUp4:CustFacade( 4039): isPhone : true
,I/LicenseContentProvider( 2735): start selecting data
,D/SIMObserver( 2735): simInfo1
,I/AppUp4:EulaManager( 4039): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4039): begin check event
D/AppUp4:Utils( 4039): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4039): Event For Nothing, skip.
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7083 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 7083): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7083): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7083): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 7083): BUILD Country: EU
,I/SystemConfig( 7083): BUILD Operator: OPEN
I/ActivityManager(  962): Killing 6674:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7103 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/SystemConfig( 7083): systemFeature RCS result false
,D/SystemConfig( 7083): refreshRcsSupport() :false
I/ActivityManager(  962): Killing 6482:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 7103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7103): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7103): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  962): Killing 6724:com.lge.email/u0a24 (adj 15): empty #17
,I/IcingCorporaProvider( 2679): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7120 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/dalvikvm( 3924): GC_FOR_ALLOC freed 381K, 2% free 37960K/38604K, paused 31ms, total 34ms
,D/HyLog   ( 7120): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7120): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7120): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 7120): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 7120): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7120): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 7120): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 7120): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 7120): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7120): VFY: replacing opcode 0x6e at 0x004f
,I/IcingCorporaProvider( 2679): UpdateCorporaTask done [took 317 ms] updated apps [took 317 ms] 
,W/BaseRuntimeLoader( 7120): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7120): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7120): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 7120): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/Finsky  ( 7120): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7120): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7120): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 7120): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7120): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 7120): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 7120): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7120): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 7120): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 7120): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 7120): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 7120): VFY: replacing opcode 0x6e at 0x029a
,I/dalvikvm( 7120): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 7120): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7120): VFY: replacing opcode 0x6e at 0x001a
I/ActivityManager(  962): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=7157 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/dalvikvm(  275): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+3ms, total 30ms
,D/HyLog   ( 7157): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7157): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 7157): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/dalvikvm( 7120): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 7120): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 7120): VFY: replacing opcode 0x6e at 0x0049
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+3ms, total 24ms
,D/Finsky  ( 7120): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7120): [1] 2.run: Finished loading 1 libraries.
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 24ms
,D/PackageBroadcastService( 1944): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1944): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1944): updateResources: need to parse f{com.google.android.gms}
,V/DownloadManager( 7157): DownloadService onCreate
,I/DownloadManager( 7157): in removeSpuriousFiles
,V/DownloadManager( 7157): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7157): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 7157): created cursor android.database.sqlite.SQLiteCursor@428a8dc0 on behalf of 7120
,V/DownloadManager( 7157): created cursor android.database.sqlite.SQLiteCursor@428aa418 on behalf of 7157
,V/DownloadManager( 7157): DownloadService onStartCommand
,V/DownloadManager( 7157): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 7157): in trimDatabase
,V/DownloadManager( 7157): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 7157): created cursor android.database.sqlite.SQLiteCursor@428adbd0 on behalf of 7157
,V/DownloadManager( 7157): created cursor android.database.sqlite.SQLiteCursor@428aea80 on behalf of 7157
,D/Finsky  ( 7120): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 7157): DownloadService onDestroy
,D/Finsky  ( 7120): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  962): Killing 6757:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 7120): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 7120): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7120): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7120): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7120): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1526): GC_EXPLICIT freed 1185K, 28% free 18011K/24832K, paused 3ms+6ms, total 45ms
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  962): GC_EXPLICIT freed 2167K, 49% free 30748K/59360K, paused 4ms+13ms, total 157ms
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7120): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dalvikvm( 7120): Total arena pages for JIT: 11
,I/dalvikvm( 7120): Total arena pages for JIT: 12
I/dalvikvm( 7120): Total arena pages for JIT: 13
,I/dalvikvm( 7120): Total arena pages for JIT: 14
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/CaptivePortalTracker(  962): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  271): _dns_getaddrinfo: iptype =1
,D/libc    (  271): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/CaptivePortalTracker(  962): Checking http://216.58.209.46/generate_204
D/QcConnectivityService(  962): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  962): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  962): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  962): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  962): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 7120): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7120): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7120): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7120): [1] DailyHygiene.reschedule: Scheduling new run in 270 minutes (failures=4)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GAV4    ( 7040): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  962): Killing 6774:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1453986810886148590; DSPS: 43290226; Offset: 1453985489773294587
,TIME-OUT KILL (timeout was 1200000ms),D/Finsky  ( 7120): [519] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7120): [1] 5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 7230): 
D/AndroidRuntime( 7230): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7230): CheckJNI is OFF
D/dalvikvm( 7230): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7230): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7230): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7230): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7230): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 7230): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 7230): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7230): failed to load memtrack module: -2
D/AndroidRuntime( 7230): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  962): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
I/ActivityManager(  962): Killing 6883:com.test.thalitest/u0a304 (adj 15): stop com.test.thalitest
I/MDM     (  962):  removeProcessLocked app.persistent = false callerWillRestart = false
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
W/PackageSettings(  962): Skipping PackageSetting{42d4c900 com.example.hello/10312} due to missing metadata
I/ActivityManager(  962): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm( 1488): GC_EXPLICIT freed 3956K, 14% free 60358K/69456K, paused 1ms+3ms, total 25ms
D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/dalvikvm( 2679): GC_EXPLICIT freed 4715K, 27% free 18160K/24832K, paused 2ms+4ms, total 48ms
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
E/SlideAside( 4062): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  962): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7249 uid=10090 gids={50090}
D/AppUp4:Utils( 4039): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 4039): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4039):  isExcludedPackage  packagename = com.test.thalitest
I/SlideAside( 4062): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/System.err( 2662): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/AppUp4  ( 4039):  isExcludedPackage TRUE : com.test.thalitest
W/System.err( 2662): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2662): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2662): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/GeofencerStateMachine( 1422): Ignoring removeGeofence because network location is disabled.
W/System.err( 2662): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2662): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2662): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2662): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2662): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2662): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2662): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "smsto"
W/System.err( 2662): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2662): 	at dalvik.system.NativeStart.main(Native Method)
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/HyLog   ( 7249): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7249): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7249): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  962): GC_EXPLICIT freed 1304K, 49% free 30769K/59360K, paused 4ms+7ms, total 126ms
D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 96ms
I/ActivityManager(  962): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7272 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
W/ActivityManager(  962): getAssistContextExtras failed: no resumed activity
D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1140): changeTargets() succeeded. size: 20
D/KeyguardModel( 1140): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "mmsto"
I/LockScreenSettings( 7249): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/HyLog   ( 7272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7272): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7272): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1140): createShortcutInfo...
D/administrator(  962): Handling package changes for user 0
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1140): createShortcutInfo...
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
I/PackageManager(  962):   Scheme: "sms"
D/[BNRAppListMgrReceiver]( 7272): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "smsto"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1140): handleShortcutListChanged...
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "mmsto"
D/VoicemailCleanupService( 1806): Cleaning up data for package: com.test.thalitest
D/KeyguardModel( 1140): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1140): createShortcutInfo...
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7287 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
D/KeyguardModel( 1140): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1140): createShortcutInfo...
D/KeyguardModel( 1140): handleShortcutListChanged...
I/ActivityManager(  962): Killing 6794:com.lge.drmservice/u0a66 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 7287): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7287): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7287): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  962): updateIntentFilterConfig
I/InteractionManagerConfigurator(  962): com.test.thalitest isn't inclued in dragdropPackageList
V/BackupManagerService(  962): removePackageParticipantsLocked: uid=10304 #1
D/dalvikvm(  962): GC_EXPLICIT freed 575K, 49% free 30727K/59360K, paused 7ms+21ms, total 211ms
I/LGEmail ( 7287): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/LGEmail ( 7287): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
W/BaseRuntimeLoader( 7287): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7287): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7287): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7287): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/PackageChangeReceiver( 7287): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AndroidRuntime( 7230): Shutting down VM
D/dalvikvm( 7230): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
D/PackageIntentReceiver( 2610): Not supported Hotkey customization function 
I/ActivityManager(  962): Killing 6807:com.lge.lgdmsgcm/1000 (adj 15): empty #17
D/HideNavigationAppsReceiver( 2610): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2610): Delete mPackageMame : com.test.thalitest
I/IcingCorporaProvider( 2679): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c62080 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  962): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7309 uid=10073 gids={50073, 3003, 1028, 1015}
D/HyLog   ( 7309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7309): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7309): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/IcingCorporaProvider( 2679): UpdateCorporaTask done [took 84 ms] updated apps [took 83 ms] 
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  266): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
