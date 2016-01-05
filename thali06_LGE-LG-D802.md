#### Test 54968200254eab2_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 1555): GC_EXPLICIT freed 796K, 29% free 17863K/24836K, paused 2ms+6ms, total 38ms
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/BaseAppContext( 1965): Using Auth Proxy for data requests.
W/GAV2    ( 4726): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  963): Killing 4142:com.google.android.configupdater/u0a3 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2}
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  963): handleMessage: X
D/dalvikvm( 1965): GC_CONCURRENT freed 1619K, 22% free 19457K/24836K, paused 4ms+5ms, total 42ms
D/dalvikvm( 1965): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/dalvikvm( 1965): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/ConfigFetchTask( 1965):   purging config for com.example.hello
I/ConfigFetchService( 1965): fetch service done; releasing wakelock
I/ConfigFetchService( 1965): stopping self
D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1965): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 272 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1220): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  963): battery changed pluggedType: 2
I/Icing   ( 1965): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1965): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1965): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.437225 Y: -0.405945 Z: 9.823761 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.437225 .y:-0.405945 .z:9.823761
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/AndroidRuntime( 4780): 
D/AndroidRuntime( 4780): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4780): CheckJNI is OFF
D/dalvikvm( 4780): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4780): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4780): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4780): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4780): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4780): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.432587 Y: -0.423492 Z: 9.815079 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.432587 .y:-0.423492 .z:9.815079
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
E/memtrack( 4780): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4780): failed to load memtrack module: -2
D/AndroidRuntime( 4780): Calling main entry com.android.commands.am.Am
I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4780
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (114 us)
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  963): startService SlideAside
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{43328188 stackId=1, 2 tasks}
W/ContextImpl(  963): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/AndroidRuntime( 4780): Shutting down VM
D/UsbSettingsControl( 2611): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2611): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4780): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 8ms
I/SlideAside( 3740): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  963): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4797 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3740): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3740): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4797): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4797): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4797): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4797): Binding Chromium to the background looper Looper (main, tid 1) {428a4c08}
I/chromium( 4797): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4797): Initializing chromium process, renderers=0
W/chromium( 4797): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4797): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4797): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4797): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4797): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4797): Remote Branch: 
I/Adreno-EGL( 4797): Local Patches: 
I/Adreno-EGL( 4797): Reconstruct Branch: 
I/dalvikvm( 4797): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4797): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4797): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4797): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4797): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4797): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4797): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4797): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4797): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4797): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4797): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4797): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4797): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4797): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4797): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4797): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4797): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4797): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4797): CordovaWebView is running on device made by: LGE
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/dalvikvm( 4797): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4797): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4797): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4797): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4797): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4797): Enabling debug mode 0
W/AwContents( 4797): nativeOnDraw failed; clearing to background color.
W/AwContents( 4797): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  963): IME STATUS OFF
I/ActivityManager(  963): Displayed com.test.thalitest/.MainActivity: +504ms
I/ActivityManager( 4797): Timeline: Activity_idle id: android.os.BinderProxy@428a63d8 time:113689
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/JsMessageQueue( 4797): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4797): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428aa9e8
D/dalvikvm( 4797): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428aa9e8
D/jxcore_app_log( 4797): JniHelper::setJavaVM(0x4176f838), pthread_self() = 1633606744
D/JX-Cordova( 4797): jxcore cordova android initializing
D/ActivityManager(  963): no-history finish of ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{431d3f90 ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3} time:113945
D/UsbSettings( 2611): [AUTORUN] onStop()
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4797): GC_CONCURRENT freed 2745K, 12% free 21894K/24836K, paused 2ms+1ms, total 39ms
D/dalvikvm( 4797): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 165K, 12% free 21914K/24836K, paused 39ms, total 39ms
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 132K, 12% free 21928K/24836K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 23.683MB for 96598-byte allocation
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 180K, 12% free 21962K/24932K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 23.763MB for 144892-byte allocation
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 253K, 13% free 22010K/25076K, paused 22ms, total 22ms
I/dalvikvm-heap( 4797): Grow heap (frag case) to 23.879MB for 217334-byte allocation
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 370K, 13% free 22085K/25292K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 24.055MB for 325996-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 570K, 14% free 22207K/25612K, paused 35ms, total 36ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 24.330MB for 488990-byte allocation
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 871K, 15% free 22383K/26092K, paused 38ms, total 39ms
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 1288K, 14% free 22641K/26092K, paused 31ms, total 32ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 25.336MB for 1100216-byte allocation
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/dalvikvm( 4797): GC_CONCURRENT freed 1770K, 16% free 23030K/27168K, paused 1ms+3ms, total 40ms
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 292K, 16% free 22960K/27168K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 26.172MB for 1650320-byte allocation
,D/dalvikvm( 4797): GC_CONCURRENT freed 1726K, 19% free 23544K/28780K, paused 1ms+3ms, total 36ms
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 1296K, 18% free 23604K/28780K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 27.589MB for 2475476-byte allocation
,D/dalvikvm( 4797): GC_CONCURRENT freed 181K, 17% free 26000K/31200K, paused 2ms+2ms, total 36ms
,D/dalvikvm( 4797): GC_CONCURRENT freed 4459K, 22% free 24604K/31200K, paused 2ms+10ms, total 70ms
,D/dalvikvm( 4797): WAIT_FOR_CONCURRENT_GC blocked 75ms
,I/dalvikvm-heap( 4797): Grow heap (frag case) to 29.746MB for 3713210-byte allocation
,D/dalvikvm( 4797): GC_CONCURRENT freed 2818K, 27% free 25692K/34828K, paused 2ms+3ms, total 48ms
,D/dalvikvm( 4797): GC_FOR_ALLOC freed 869K, 27% free 25557K/34828K, paused 26ms, total 26ms
,W/jxcore-log( 4797): Initializing JXcore engine
,W/jxcore-log( 4797): JXcore engine is ready
,D/dalvikvm( 4797): GC_CONCURRENT freed 333K, 19% free 28245K/34828K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 4797): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 4797): Starting JXcore engine
,W/jxcore-log( 4797): Platform android
W/jxcore-log( 4797): 
,W/jxcore-log( 4797): Process ARCH arm
W/jxcore-log( 4797): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV2    ( 4726): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4797): JXcore Cordova bridge is ready!
I/jxcore-log( 4797): 
,W/jxcore-log( 4797): JXcore engine is started
,I/chromium( 4797): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4797): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4797): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/ConfigService( 1555): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/jxcore-log( 4797): Toggling radios to true
I/jxcore-log( 4797): 
,D/BluetoothManagerService(  963): Message: 20
,D/BluetoothManagerService(  963): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ddeaa0:true
,D/BluetoothAdapter( 4797): enable(): BT is already enabled..!
D/WifiService(  963): New client listening to asynchronous messages
,D/WifiStateMachine(  963): handleMessage: E msg.what=131145
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doBoolean: DISCONNECT
,I/jxcore-log( 4797): Radios toggled
I/jxcore-log( 4797): 
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2023): TDLS: Tear down peers
,D/wpa_supplicant( 2023): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  963): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4797): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4797): 
,I/jxcore-log( 4797): Perf Test app loaded loaded
I/jxcore-log( 4797): 
D/WifiService(  963): setWifiEnabled: true pid=4797, uid=10304
E/WifiService(  963): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  963): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  963): disconnect pid=4797, uid=10304
D/WifiService(  963): reconnect pid=4797, uid=10304
,D/wpa_supplicant( 2023): wlan0: Event DEAUTH (12) received
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
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb81ddd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> DISCONNECTED
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
D/wpa_supplicant( ,2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2023): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: ConnectedState
W/Settings(  963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
I/chromium( 4797): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Choreographer( 4797): Skipped 60 frames!  The application may be doing too much work on its main thread.
D/WifiStateMachine(  963): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  963): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131146
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiNative-wlan0(  963): doBoolean: RECONNECT
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2023): Fast associate: Old scan results
D/wpa_supplicant( 2023): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2023): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2023): wlan0: nl80211: scan request
D/wpa_supplicant( 2023): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147460
D/WifiStateMachine(  963): processMsg: DisconnectingState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection lost
D/WifiStateMachine(  963): Stopping DHCP and clearing IP
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/wpa_supplicant( 2023): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  963):    returned true
,D/DhcpStateMachine(  963): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4797): check test folder
I/jxcore-log( 4797): 
D/WifiStateMachine(  963): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
I/jxcore-log( 4797): found test : ./testFindPeers.js
I/jxcore-log( 4797): 
,D/WifiStateMachine(  963): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/WifiHS20(  963): hidePasspointNotification off =false
D/QcConnectivityService(  963): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/jxcore-log( 4797): found test : ./testSendData.js
I/jxcore-log( 4797): 
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
D/QCNEA   (  471): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  471): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  471): |CAC| updateNetCfgInfo
V/QCNEA   (  471): |CAC| *********************************************
V/QCNEA   (  471): |CAC|                   Netconfig               
V/QCNEA   (  471): |CAC| *********************************************
V/QCNEA   (  471): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  471): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  471): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  471): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  471): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  471): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  471): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  471): |CAC| *********************************************
D/QCNEA   (  471): |CAC| Received bssid= 
D/QCNEA   (  471): |CAC| net type = 3
V/QCNEA   (  471): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  471): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  471): |CAC| 	ssid           =NG700
V/QCNEA   (  471): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  471): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  471): |CAC| *********************************************
D/QCNEA   (  471): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  471): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  471): |CAC| dispatchNetCfg: updating:0xb85dc8dc
,D/QCNEA   (  471): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  471): Reading a NULL string not supported here.
,E/Parcel  (  471): Reading a NULL string not supported here.
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QcConnectivityService(  963): Attempting to switch to mobile
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  963): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=1 connState=2
I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4859 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/WifiStateMachine(  963): transitionTo: destState=DisconnectedState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=5
,D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  963): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): handleMessage: X
D/NetworkManagementService(  963): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  963): handleMessage: E msg.what=131213
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): handleMessage: X
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
D/HyLog   ( 4859): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4859): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4859): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/PCSuite ( 4859): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 4859): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4859): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
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
,D/NetUtils(  963): android_net_utils_resetConnections in env=0x61e3eef0 clazz=0x6cd00001 iface=wlan0 mask=0x3
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): handleMessage: X
D/QcConnectivityService(  963): resetConnections(wlan0, 3)
I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4892 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  963): Killing 4291:com.google.android.talk/u0a77 (adj 15): empty #17
D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4892): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4892): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/NativeCrypto( 1555): Read error: ssl=0x62614c60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1555): SSL shutdown failed: ssl=0x62614c60: I/O error during system call, Broken pipe
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4892): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  963): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 4892): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
I/QRemote ( 4892): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4892): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4892): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/QRemote ( 4892): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4892): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4892): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4892): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  963): Killing 2138:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
,D/DhcpStateMachine(  963): StoppedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4332): onReceive
D/wpa_supplicant( 2023): nl80211: Event message available
D/wpa_supplicant( 2023): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2023): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2023): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2023): nl80211: Received scan results (12 BSSes)
D/wpa_supplicant( 2023): nl80211: Survey data missing
D/wpa_supplicant( 2023): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 7 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 9 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 10 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Add new id 11 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): BSS: last_scan_res_used=12/32 last_scan_full=0
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
D/wpa_supplicant( 2023): WPS: AP 44:e9:dd:10:c0:ac type 0 added
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2023): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2023): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[4] 44:e9:dd:10:c0:ac type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): WPS: AP[6] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2023): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2023): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 1: c2:ff:d4:d3:aa,:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-47
D/wpa_supplicant( 2023): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2023): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-53 wps
D/wpa_supplicant( 2023): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2023): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81df5a8  current_ssid=0x0
D/wpa_supplicant( 2023): scard is not null..
D/wpa_supplicant( 2023): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2023): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01,
,D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
,D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
,D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00,
,D/wpa_supplicant( 2023): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2023): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2023): wlan0: Cancelling scan request
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 2023): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2023): RSN: PMKSA cache search - network_ctx=0xb81df5a8 try_opportunistic=0
D/wpa_supplicant( 2023): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2023): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2023): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
,D/wpa_supplicant( 2023): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2023): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2023): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2023): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2023): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2023): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2023): wlan0: State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
,D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2023): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2023): nl80211: Unsubscribe mgmt frames handle 0xb81de590 (mode change)
D/wpa_supplicant( 2023): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81de590,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590,
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0c,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09,
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 04 0e
,D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590,
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
,D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2023): nl80211: Register frame type=0xd0 nl_handle=0xb81de590
D/wpa_supplicant( 2023): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2023): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2023):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 2023):   * freq=2412
D/wpa_supplicant( 2023):   * SSID - hexdump(len=5): 4e 47 37 30 30,
,D/wpa_supplicant( 2023):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023):   * Auth Type 0
D/wpa_supplicant( 2023):   * WPA Versions 0x2
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ac],
D/wpa_supplicant( 2023): nl80211: Connect request send successfully
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2023): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2023): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 10:9a:dd:8e:22:d9]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 64:7c:34:38:27:cc]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 06:7c:34:38:27:cc]
D/WifiStateMachine(  963): handleMessage: E msg.what=147461
D/WifiStateMachine(  963): processMsg: DisconnectedState,
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  963): doString: BSS RANGE=0- MASK=0x21987,
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2023): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311),
,D/wpa_supplicant( 2023): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
W/WifiMonitor(  963): couldn't identify event type - WPS-AP-AVAILABLE 
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine(  963): processMsg: ConnectModeState
,D/WifiStateMachine(  963): handleMessage: X
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
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  963): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 39 b6 d0 30 d7 ae 56 1f 24 af 41 a6 5f b1 f5 ...
D/wpa_supplicant( 2023): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=0
D/AppUp4:CustFacade( 4332): Context : android.app.ReceiverRestrictedContext@428bb240
D/AppUp4:CustFacade( 4332): isCustomizationCompleted : false
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/AppUp4:CustFacade( 4332): isOpenOperator : true
D/AppUp4:CustFacade( 4332): isPhone : true
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 39 b6 d0 30 d7 ae 56 1f 24 af 41 a6 5f b1 f5 ba b0 66 d4 4a 17 bd 8c f5 d7 42 5c bb 2f 7d cf b4
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 39 b6 d0 30 d7 ae 56 1f 24 af 41 a6 5f b1 f5 ...
D/wpa_supplicant( 2023): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2023): Get randomness: len=32 entropy=11
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/wpa_supplicant( 2023): WPA: Renewed SNonce - hexdump(len=32): be 3b 48 90 5a 5d b1 50 88 87 b2 7b c0 98 0c 08 d9 b0 ca b3 6c 8e 1a c3 f0 50 42 8f 05 39 80 ad
D/wpa_supplicant( 2023): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): WPA: Nonce1 - hexdump(len=32): be 3b 48 90 5a 5d b1 50 88 87 b2 7b c0 98 0c 08 d9 b0 ca b3 6c 8e 1a c3 f0 50 42 8f 05 39 80 ad
D/wpa_supplicant( 2023): WPA: Nonce2 - hexdump(len=32): 39 b6 d0 30 d7 ae 56 1f 24 af 41 a6 5f b1 f5 ba b0 66 d4 4a 17 bd 8c f5 d7 42 5c bb 2f 7d cf b4
D/wpa_supplicant( 2023): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2023): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 69 87 0b 18 60 08 90 45 bb d6 4d 9c c4 f8 e3 74
D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 be 3b 48 90 5a 5d b1 50 88 87 b2 7b c0 98 0c ...
I/LicenseContentProvider( 4355): start selecting data
D/SIMObserver( 4355): simInfo1
I/AppUp4:EulaManager( 4332): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4332): begin check event
I/AppUp4:CustModeStarterReceiver( 4332): Event For GoodConnectivity, noConnectivity : true, but skip! 
D/wpa_supplicant( 2023): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 39 b6 d0 30 d7 ae 56 1f 24 af 41 a6 5f b1 f5 ...
D/wpa_supplicant( 2023): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2023): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2023): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2023): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2023):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2023):   key_nonce - hexdump(len=32): 39 b6 d0 30 d7 ae 56 1f 24 af 41 a6 5f b1 f5 ba b0 66 d4 4a 17 bd 8c f5 d7 42 5c bb 2f 7d cf b4
D/wpa_supplicant( 2023):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_rsc - hexdump(len=8): 70 66 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2023):   key_mic - hexdump(len=16): 34 58 e2 37 69 9a 8e a5 09 1a 5c 7a 01 b1 be aa
D/wpa_supplicant( 2023): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 39 b6 d0 30 d7 ae 56 1f 24 af 41 a6 5f b1 f5 ...
D/wpa_supplicant( 2023): RSN: encrypted key data - hexdump(len=56): cf 93 49 3c a0 e1 76 06 2e 5c b2 05 de ba c3 9d a3 50 2c e6 0a 61 9d eb e1 89 49 5f 23 0f 26 b2 ...
D/wpa_supplicant( 2023): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2023): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2023): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 83 e9 ...
D/wpa_supplicant( 2023): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2023): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2023): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): WPA: Derived Key MIC - hexdump(len=16): 09 04 dd 7a e2 f3 50 b5 d7 d8 ae 25 ef 93 1f b8
D/wpa_supplicant( 2023): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2023): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb81dec54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2023):    addr=c0:ff:d4:d3:aa:48
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2023): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2023): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2023): WPA: RSC - hexdump(len=6): 70 66 00 00 00 00
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f5103a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 2023):    broadcast key
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: DisconnectedState
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
I/wpa_supplicant( 2023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2023): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/WifiMonitor(  963): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
I/wpa_supplicant( 2023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
W/WifiMonitor(  963): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2023): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2023): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2023): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2023): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2023): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2023): EAP: EAP entering state DISABLED
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2023): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2023): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2023): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2023): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2023): EAPOL authentication completed successfully
D/wpa_supplicant( 2023): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2023): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2023): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: DisconnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): Network connection established
D/WifiNative-wlan0(  963): doString: STATUS
I/ActivityManager(  963): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4942 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2023): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  963):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  963): ssid=NG700
D/WifiNative-wlan0(  963): id=0
D/WifiNative-wlan0(  963): mode=station
D/WifiNative-wlan0(  963): pairwise_cipher=CCMP
D/WifiNative-wlan0(  963): group_cipher=CCMP
D/WifiNative-wlan0(  963): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  963): wpa_state=COMPLETED
D/WifiNative-wlan0(  963): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  963): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  963): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  963): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  963): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/WifiStateMachine(  963): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  963): invokeExitMethods: DisconnectedState
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
D/WifiStateMachine(  963): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  963): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ObtainingIpState
D/DhcpStateMachine(  963): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  963): WaitBeforeStartState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-16ms what=147462 obj=android.net.wifi.StateChangeResult@444db8e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147462
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@444bdbc8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=147459
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-10ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
D/HyLog   ( 4942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/HyLog   ( 4942): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
D/HyLog   ( 4942): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2023): nl80211: survey data missing!
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196612
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 1
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,V/DownloadManager( 4942): DownloadService onCreate
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4942): in removeSpuriousFiles
,D/eas_req ( 4707): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4942): DownloadService onStartCommand
,I/LgeMiscReceiver( 4495): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4495): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4942): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 4495): networkInfo.isConnected() = false
,V/DownloadManager( 4942): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428ebde8 on behalf of 4942
,W/linker  ( 4707): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/DownloadManager( 4942): in trimDatabase
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428edc80 on behalf of 4942
V/DownloadManager( 4942): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/HtmlEditor( 4707): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4707): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4707): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4707): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428f04c8 on behalf of 4942
D/HtmlEditor( 4707): register_HtmlEditor, Success
,D/HtmlEditor( 4707): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4707): register_HtmlEditorTimer, Success
,D/HtmlEditor( 4707): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4707): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4707): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4707): register_HtmlEditorFont, Success
,D/HtmlEditor( 4707): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4707): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4707): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4707): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4707): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4707): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4707): JNI_OnLoad Success
V/DownloadManager( 4942): DownloadService onDestroy
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  963): doBoolean: SET ps 0
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  963):    returned true
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  963): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  963):    returned null
E/WifiStateMachine(  963): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  963): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  963): DHCP Start wake lock is acquired.
,D/CommandListener(  264): Setting iface cfg
I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4966 uid=10052 gids={50052, 3003}
D/WifiP2pService(  963): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432dbb58 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  963): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432dbb58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  963): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-3ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
D/WifiStateMachine(  963): processMsg: DefaultState
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=196613
D/WifiStateMachine(  963): processMsg: ObtainingIpState
D/WifiStateMachine(  963): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  963): doBoolean: SET ps 1
I/HubEmail( 4707): JNI_OnLoad()
I/HubEmail( 4707): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4707): registerNatives()
I/HubEmail( 4707): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4707): registerNativeMethods()
I/HubEmail( 4707): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2023): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2023): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2023): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
W/Settings( 4707): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  963):    returned true
D/WifiNative-wlan0(  963): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  963):    returned true
,D/WifiStateMachine(  963): DHCP successful
D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/HyLog   ( 4966): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  963): transitionTo: destState=VerifyingLinkState
D/HyLog   ( 4966): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/HyLog   ( 4966): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  963): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  963): VerifyingLinkState enter
,D/WifiStateMachine(  963): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  963): send additional Connectivity Action
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  963): handleMessage: E msg.what=135190
D/WifiStateMachine(  963): processMsg: VerifyingLinkState
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
D/WifiStateMachine(  963): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
E/Parcel  (  471): Reading a NULL string not supported here.
,D/WifiStateMachine(  963): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  963): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): CaptivePortalCheckState enter
,D/WifiStateMachine(  963): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/WifiP2pService(  963): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  963): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiStateTracker(  963): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  963): 
W/WifiStateTracker(  963):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  963):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WifiStateMachine(  963): handleMessage: X
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  963): handleMessage: E msg.what=131092
D/WifiStateMachine(  963): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  963): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
I/ActivityManager(  963): Killing 3901:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/QcConnectivityService(  963): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  963): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
D/WifiStateMachine(  963): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  963): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  963): handleMessage: new destination call exit/enter
D/WifiStateMachine(  963): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  963): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  963): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  963): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  963): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  963): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
,E/Parcel  (  471): Reading a NULL string not supported here.
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  963): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,V/LGRssiData( 4966): [loadRssi] File not exist 
V/LGRssiData( 4966): [loadRssi] File not exist 
D/MobileConnectivityChangeReceiver( 4966): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/TelephonyAutoProfiling( 4966): [loadFeatureFromXml] *** start feature loading from xml
D/MobileConnectivityChangeReceiver( 4966): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 4966): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4966): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
V/        (  264): RouteController
,V/        (  264): RouteController
W/BaseRuntimeLoader( 4966): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4966): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4966): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4966): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4966): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/        (  264): RouteController
E/PhoneMonitor( 4966): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4966): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,V/        (  264): RouteController
I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4986 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  963): Killing 4470:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,V/        (  264): RouteController
,V/        (  264): RouteController
I/CheckinService( 1965): Checking schedule, now: 1451954428468 next: 1451954368945
,I/CheckinService( 1965): active receiver: enabled
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
V/        (  264): RouteController
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
,D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4986): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4986): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/CheckinService( 1965): Preparing to send checkin request
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QCNEA   (  471): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  471): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  471): |CAC| updateNetCfgInfo
V/QCNEA   (  471): |CAC| *********************************************
V/QCNEA   (  471): |CAC|                   Netconfig               
V/QCNEA   (  471): |CAC| *********************************************
V/QCNEA   (  471): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  471): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  471): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  471): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  471): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  471): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  471): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  471): |CAC| *********************************************
D/QCNEA   (  471): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  471): |CAC| net type = 1
V/QCNEA   (  471): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  471): |CAC| Received ssid= NG700
,V/QCNEA   (  471): |CAC| 	ssid           =NG700
V/QCNEA   (  471): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  471): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  471): |CAC| *********************************************
D/QCNEA   (  471): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  471): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  471): |CAC| dispatchNetCfg: updating:0xb85dc8dc
D/QCNEA   (  471): |CAC| readCallback: read len:0, ret:-1, errno:11
I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/EventLogService( 1965): Accumulating logs since 1451954335200
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,D/DhcpStateMachine(  963): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  963): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/dalvikvm(  963): GC_EXPLICIT freed 23762K, 49% free 29754K/58036K, paused 3ms+7ms, total 126ms
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5017 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  963): Killing 4646:com.android.defcontainer/u0a4 (adj 15): empty #17
,E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5017): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5017): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  963): Killing 4200:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5038 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/HyLog   ( 5038): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5038): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5038): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5038): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5061 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  963): Killing 4693:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
,D/HyLog   ( 5061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5061): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5061): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
,I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5061): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 5061): intf.getDisplayName() = lo
I/Wireless_Storage( 5061): intf.getDisplayName() = sit0
I/Wireless_Storage( 5061): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5061): intf.getDisplayName() = teql0
I/Wireless_Storage( 5061): intf.getDisplayName() = wlan0
,D/NFS     ( 5061): interface name:wlan0 name:wlan0
D/NFS     ( 5061): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 5061): interface name:wlan0 name:wlan0
D/NFS     ( 5061): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
,I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5076 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 4368:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24836K, paused 1ms+1ms, total 17ms
D/HyLog   ( 5076): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5076): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5076): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 1ms+1ms, total 14ms
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24836K, paused 0ms+2ms, total 13ms
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/GAV2    ( 5076): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x42dfcd80: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ActivityManager(  963): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5093 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 5093): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5093): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5093): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 5093): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5093): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 5093): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5093): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5093): VFY: replacing opcode 0x62 at 0x005e
I/MultiDex( 5093): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5093): install
,I/MultiDex( 5093): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 5093): loading existing secondary dex files
,I/MultiDex( 5093): load found 3 secondary dex files
,I/MultiDex( 5093): install done
,D/dalvikvm( 5093): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5093): VFY: unable to resolve instance field 61
,D/dalvikvm( 5093): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 5093): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5093): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5093): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 5093): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5093): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5093): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5093): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5093): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 5093): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428aa398
D/dalvikvm( 5093): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428aa398
,D/dalvikvm( 5093): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428aa398, skipping init
,D/dalvikvm( 5093): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428aa398
D/dalvikvm( 5093): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428aa398
,V/JNIHelp ( 5093): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/WebViewChromium( 5076): Binding Chromium to the main looper Looper (main, tid 1) {428ae448}
,I/chromium( 5076): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5076): Initializing chromium process, renderers=0
,W/chromium( 5076): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5076): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5076): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5076): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5076): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5076): Remote Branch: 
I/Adreno-EGL( 5076): Local Patches: 
I/Adreno-EGL( 5076): Reconstruct Branch: 
,D/dalvikvm( 5093): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428aa398
D/dalvikvm( 5093): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428aa398
D/dalvikvm( 5093): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428aa398
,D/dalvikvm( 5093): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428aa398
,D/DhcpStateMachine(  963): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  963): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  963): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  963): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  963): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  963): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  963): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  963): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  963): RunningState
,I/NSApplication( 5076): Starting up...
,I/ActivityManager(  963): Killing 4382:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3}
,D/QRemote ( 4892): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4892): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/ProviderInstaller( 5093): Installed default security provider GmsCore_OpenSSL
,D/QRemote ( 4892): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4892): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4892): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4892): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4859): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4859): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4892): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4892): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4892): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4892): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1555): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1555): Proximity feature is not enabled.
I/dalvikvm( 5093): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 5093): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5093): VFY: replacing opcode 0x6e at 0x000d
,V/GmsCoreStatsServiceLauncher( 1965): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/dalvikvm( 5093): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 5093): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5093): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1965): Restart initialization of location
,D/WearableService( 1874): callingUid 10006, callindPid: 1874
,E/MDM     ( 1423): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fba000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1fba000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1220): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1220): Disconnected process message: 10
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  963): battery changed pluggedType: 2
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=171723980
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5093): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a7cf88
D/dalvikvm( 5093): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a7cf88
,D/dalvikvm( 5093): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a7cf88, skipping init
D/wpa_supplicant( 2023): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2023): EAPOL: disable timer tick
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
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
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3758668325
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  963): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 5093): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 5138): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/dalvikvm( 5093): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5093): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 78ms
,I/Adreno-EGL( 5093): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5093): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5093): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5093): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5093): Remote Branch: 
I/Adreno-EGL( 5093): Local Patches: 
I/Adreno-EGL( 5093): Reconstruct Branch: 
,I/Adreno-EGL( 5093): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5093): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5093): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5093): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5093): Remote Branch: 
I/Adreno-EGL( 5093): Local Patches: 
I/Adreno-EGL( 5093): Reconstruct Branch: 
,D/WifiStateMachine(  963): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  963): handleMessage: E msg.what=131212
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
D/WifiStateMachine(  963): processMsg: SupplicantStartedState
,D/WifiStateMachine(  963): processMsg: DefaultState
,D/WifiStateMachine(  963): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  963): send additional Connectivity Action
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,D/LocSvc_java(  963): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  963): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiStateMachine(  963): handleMessage: X
D/QcConnectivityService(  963): handleConnectivityChange:1 is conntected
,W/Settings( 5093): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/QcConnectivityService(  963): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  963):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  963): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  963): requiresClat: netType=1, hasIPv4Address=true
D/GpsLocationProvider(  963): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1448): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/dalvikvm( 4797): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4797): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4797): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 4797): Shutting down VM
,W/dalvikvm( 4797): threadid=1: thread exiting with uncaught exception (group=0x4186ae48)
E/AndroidRuntime( 4797): FATAL EXCEPTION: main
E/AndroidRuntime( 4797): Process: com.test.thalitest, PID: 4797
E/AndroidRuntime( 4797): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4797): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4797): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4797): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4797): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4797): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4797): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4797): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4797): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4797): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4797): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4797): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4797): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4797): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  963):   Force finishing activity com.test.thalitest/.MainActivity
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f}
,D/GCM     ( 1555): Connected
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1555): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Adreno-EGL( 5093): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5093): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5093): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5093): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5093): Remote Branch: 
I/Adreno-EGL( 5093): Local Patches: 
I/Adreno-EGL( 5093): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinTask( 1965): Sending checkin request (11620 bytes)
,W/ActivityManager(  963): Activity pause timeout for ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f} (due to timeout)
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f} (finish requested)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{43328188 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/[LGHome]EVENT( 1488): [Launcher.java:4947:onStart()]onStart
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1488): [Launcher.java:717:onResume()]onResume
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,I/[LGHome]LGActivityUtil( 1488): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1488): [Launcher.java:868:onResume()]onResume end
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WeatherAncestor( 1836): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:40:30
,D/UpdateThreadPoolManager( 1836): 2 : This is isUpdating : false
,D/WeatherQuickCover( 1836): 2 : quick cover state : opened : 0
,D/WeatherService( 1836): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1836): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/WeatherAncestor( 1836): 2 : shouldTimeTickRegistered().........
,W/ContextImpl( 1836): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
,D/WeatherService( 1836): 2 : TimeTick Receiver Register
,D/WeatherAncestor( 1836): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 1:40:30
,D/WeatherService( 1836): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherQuickCover( 1836): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1836): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1836): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1836): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WeatherService( 1836): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 1836): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 1836): 2 : This is isUpdating : false
D/WeatherService( 1836): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1836): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1836): 2 : Map key string is -2
D/lim     ( 1836): 2 : time = 01:40
I/WeatherReflect( 1836): Model Name : LG-D802
D/WeatherTheme( 1836): 2 : Different view - status_min_formatted : 38 != 40
D/WeatherTheme( 1836): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1836): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1836): 2 : Fixed theme : optimus
D/WeatherTheme( 1836): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/WeatherQuickCover( 1836): 2 : quick cover state : opened : 0
D/Weather.Utils( 1836): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1836): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1836): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,D/dalvikvm( 1143): GC_FOR_ALLOC freed 7153K, 11% free 70490K/78632K, paused 32ms, total 32ms
,D/dalvikvm( 1488): GC_CONCURRENT freed 5293K, 9% free 60850K/66328K, paused 1ms+4ms, total 27ms
,D/dalvikvm( 1488): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1488): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1488): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
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
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/[LGHome]EVENT( 1488): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,D/dalvikvm( 1488): GC_FOR_ALLOC freed 5019K, 9% free 61984K/67860K, paused 23ms, total 23ms
,D/dalvikvm( 1555): GC_EXPLICIT freed 660K, 29% free 17848K/24836K, paused 2ms+3ms, total 31ms
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@428a90d8 time:123781
,D/UsbSettings( 2611): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2611): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
,V/UsbSettings( 2611): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2611): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{42c17fc0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1} time:123840
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f}
V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested)
,I/CheckinTask( 1965): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1965): Checking schedule, now: 1451954431074 next: 1452531827072
,I/CheckinService( 1965): active receiver: disabled
,D/dalvikvm(  963): GC_CONCURRENT freed 2283K, 47% free 30798K/58036K, paused 3ms+5ms, total 91ms
D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 88ms
,D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 47ms
,D/dalvikvm( 1965): GC_CONCURRENT freed 1811K, 22% free 19589K/24836K, paused 2ms+6ms, total 33ms
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x43e8f1f0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/GCM     ( 1555): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
E/Parcel  (  471): Reading a NULL string not supported here.
,E/Parcel  (  471): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4332): onReceive
,D/AppUp4:CustFacade( 4332): Context : android.app.ReceiverRestrictedContext@428bb240
D/AppUp4:CustFacade( 4332): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4332): isOpenOperator : true
,D/AppUp4:CustFacade( 4332): isPhone : true
,I/LicenseContentProvider( 4355): start selecting data
,D/SIMObserver( 4355): simInfo1
,I/AppUp4:EulaManager( 4332): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4332): begin check event
,I/AppUp4:CustModeStarterReceiver( 4332): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4332): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4332): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4332): handleAsync eula : false
,E/AppUp4:CustModeStarterReceiver( 4332): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4332): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4942): DownloadService onCreate
,I/DownloadManager( 4942): in removeSpuriousFiles
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4942): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428f5810 on behalf of 4942
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4942): in trimDatabase
V/DownloadManager( 4942): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/eas_req ( 4707): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428f6c70 on behalf of 4942
,V/DownloadManager( 4942): DownloadService onStartCommand
,V/DownloadManager( 4942): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428f8e20 on behalf of 4942
,V/DownloadManager( 4942): DownloadService onDestroy
W/Settings( 4707): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4495): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4495): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4495): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 4966): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/MobileConnectivityChangeReceiver( 4966): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 5038): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  963): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  963): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,E/BatteryObserver( 1157): usb Uevent not necessary.
E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1220): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4332): onReceive
,D/AppUp4:CustFacade( 4332): Context : android.app.ReceiverRestrictedContext@428bb240
D/AppUp4:CustFacade( 4332): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4332): isOpenOperator : true
,D/AppUp4:CustFacade( 4332): isPhone : true
,I/LicenseContentProvider( 4355): start selecting data
,D/SIMObserver( 4355): simInfo1
,I/AppUp4:EulaManager( 4332): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4332): begin check event
,I/AppUp4:CustModeStarterReceiver( 4332): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4942): DownloadService onCreate
,I/DownloadManager( 4942): in removeSpuriousFiles
,V/DownloadManager( 4942): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428fd110 on behalf of 4942
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4942): in trimDatabase
,V/DownloadManager( 4942): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@428fe578 on behalf of 4942
,V/DownloadManager( 4942): DownloadService onStartCommand
,V/DownloadManager( 4942): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 4495): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4495): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4495): networkInfo.isConnected() = true
,D/PhoneState( 4495): setPdpRejectCasuse : false
,W/Settings( 4707): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4966): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4966): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@42900b50 on behalf of 4942
,D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4942): DownloadService onDestroy
,D/LGDMSGCM( 5038): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1220): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 273 plugged : true isCharging : false
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1488): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1488): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1488): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  963): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-9ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4332): [onReceive] request level :IDLE....
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/AppUp4:CustModeStarterReceiver( 4332): onReceive
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/AppUp4:CustFacade( 4332): Context : android.app.ReceiverRestrictedContext@428bb240
,D/AppUp4:CustFacade( 4332): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4332): isOpenOperator : true
,D/AppUp4:CustFacade( 4332): isPhone : true
,I/LicenseContentProvider( 4355): start selecting data
,D/SIMObserver( 4355): simInfo1
,I/AppUp4:EulaManager( 4332): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4332): begin check event
,I/AppUp4:CustModeStarterReceiver( 4332): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4942): DownloadService onCreate
,I/DownloadManager( 4942): in removeSpuriousFiles
,V/DownloadManager( 4942): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@42904cd8 on behalf of 4942
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4707): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
V/DownloadManager( 4942): DownloadService onStartCommand
,V/DownloadManager( 4942): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@429077e8 on behalf of 4942
,I/DownloadManager( 4942): in trimDatabase
,V/DownloadManager( 4942): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/LgeMiscReceiver( 4495): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4495): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4495): networkInfo.isConnected() = true
D/PhoneState( 4495): setPdpRejectCasuse : false
V/DownloadManager( 4942): created cursor android.database.sqlite.SQLiteCursor@42909000 on behalf of 4942
V/DownloadManager( 4942): DownloadService onDestroy
D/MobileConnectivityChangeReceiver( 4966): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4966): onReceive CONNECTIVITY_CHANGE networkType=1
W/Settings( 4707): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 2874): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2874): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 5038): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 2874): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 5061): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 5061): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2874): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2874): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2874): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2874): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.440323 Y: -0.399811 Z: 9.798141 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.440323 .y:-0.399811 .z:9.798141
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.433823 Y: -0.407379 Z: 9.806747 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.433823 .y:-0.407379 .z:9.806747
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/WifiServiceExtension(  963): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  963): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 5076): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 4401): [408] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4401): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  963): Killing 4726:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  963): Killing 4859:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1157): GC_CONCURRENT freed 2887K, 11% free 25448K/28516K, paused 29ms+2ms, total 81ms
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  963): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5282 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,E/SlideAside( 3740): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,D/administrator(  963): Handling package changes for user 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3740): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "sms"
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/HyLog   ( 5282): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5282): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5282): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Babel   ( 5282): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5282): MmsConfig.loadMmsSettings
I/Babel   ( 5282): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5282): MmsConfig.loadFromDatabase
,I/MediaCodecList( 5282): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5282): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5282): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5282): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 5282): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5282): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5282): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5282): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5282): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5282): MmsConfig.loadFromResources
,V/GmsNetworkLocationProvi( 1423): DISABLE
,E/Babel   ( 5282): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5282): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/GCoreNlp( 1423): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5282): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5282): [loadRssi] File not exist 
V/LGRssiData( 5282): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5282): [loadFeatureFromXml] *** start feature loading from xml
D/LocationProviderProxy(  963): applying state to connected service
,V/TelephonyAutoProfiling( 5282): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5282): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5282): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/LocationProviderProxy(  963): applying state to connected service
,D/AppUp4:Utils( 4332): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4332): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4332): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4332): onReceive
D/AppUp4:CustFacade( 4332): Context : android.app.ReceiverRestrictedContext@428bb240
,D/AppUp4:CustFacade( 4332): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4332): isOpenOperator : true
,D/AppUp4:CustFacade( 4332): isPhone : true
I/LicenseContentProvider( 4355): start selecting data
,D/SIMObserver( 4355): simInfo1
,I/AppUp4:EulaManager( 4332): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4332): begin check event
D/AppUp4:Utils( 4332): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4332): Event For Nothing, skip.
,I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5330 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5330): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5330): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5330): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5330): BUILD Country: EU
,I/SystemConfig( 5330): BUILD Operator: OPEN
I/ActivityManager(  963): Killing 4892:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5344 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
,I/SystemConfig( 5330): systemFeature RCS result false
,D/SystemConfig( 5330): refreshRcsSupport() :false
I/ActivityManager(  963): Killing 4797:com.test.thalitest/u0a304 (adj 15): empty #17
,D/HyLog   ( 5344): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5344): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5344): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/WifiService(  963): Client connection lost with reason: 4
,W/InputDispatcher(  963): channel '43d64cb8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  963): channel '43d64cb8 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,W/InputDispatcher(  963): Attempted to unregister already unregistered input channel '43d64cb8 com.test.thalitest/com.test.thalitest.MainActivity (server)'
I/WindowState(  963): WIN DEATH: Window{43d64cb8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43d49390 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1488): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/InputMethodManagerService(  963): IME STATUS OFF
,W/InputMethodManagerService(  963): Got RemoteException sending setActive(false) notification to pid 4797 uid 10304
E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Binder  ( 1318): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1318): java.lang.NullPointerException
W/Binder  ( 1318): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1318): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1318): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1318): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
D/WifiController(  963): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  963): Killing 4942:android.process.media/u0a23 (adj 15): empty #17
I/IcingCorporaProvider( 2680): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1965): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  963): Delaying start of: ServiceRecord{44ed65c8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1965): updateResources: need to parse f{com.google.android.gms}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2680): UpdateCorporaTask done [took 222 ms] updated apps [took 222 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1220): Disconnected process message: 10
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/CaptivePortalTracker(  963): DelayedCaptiveCheckState{ when=-12ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  963): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  963): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  963): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  963): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  963): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  963): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  963): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV4    ( 5282): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/PowerManagerService(  963): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  963): [updateScreenState] screen on = false
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  963): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  963): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9423 usec
D/KnockOnPowerController(  963): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  963): hal_acquire_resources
,I/qcom_sensors_hal(  963): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  963): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  963): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  963): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  963): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  963): hal_sam_send_cancel: Sending cancel to 21
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.421371 Y: -0.408279 Z: 9.794922 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.421371 .y:-0.408279 .z:9.794922
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  963): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  963): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.429977 Y: -0.412552 Z: 9.802200 
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.429977 .y:-0.412552 .z:9.802200
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,I/Sensors (  448): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  963): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  963): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  963): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  963): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  963): proximitySensorChanged  positive = true
I/KnockOnPowerController(  963): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.446045 Y: -0.422958 Z: 9.813751 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446045 .y:-0.422958 .z:9.813751
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.451309 Y: -0.408478 Z: 9.805984 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451309 .y:-0.408478 .z:9.805984
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.441132 Y: -0.400162 Z: 9.796051 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441132 .y:-0.400162 .z:9.796051
D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1,
V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.429855 Y: -0.411301 Z: 9.813370 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.429855 .y:-0.411301 .z:9.813370
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  963): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  963): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  963): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  963): hal_process_report_ind: X: -0.428360 Y: -0.402725 Z: 9.817413 
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.428360 .y:-0.402725 .z:9.817413
,D/qcom_sensors_hal(  963): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=0
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb7f9d450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/KeyguardServiceDelegate(  963): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@433f2770)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  963): **** SHOWN CALLED ****
I/WindowManager(  963): No lock screen! windowToken=null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
,D/WifiStateMachine(  963): handleScreenStateChanged: true
,D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  963): doString: SIGNAL_POLL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2023): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  963): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  963): stopMonitoring
,D/wpa_supplicant( 2023): nl80211: survey data missing!
,D/WifiStateMachine(  963): handleMessage: X
,D/WifiStateMachine(  963): handleMessage: E msg.what=131127
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
,D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  963): handleMessage: X
D/WifiStateMachine(  963): handleMessage: E msg.what=132097
D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  963): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2023): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 2023): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  963): handleMessage: X
,E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 963
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
,V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{428b7c88 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/WeatherAncestor( 1836): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:40:45
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3740): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3740): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/UpdateThreadPoolManager( 1836): 2 : This is isUpdating : false
,D/WeatherAncestor( 1836): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 1:40:45
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/WeatherService( 1836): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1836): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1836): 2 : TimeTick Receiver Unregister
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1836): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
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
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  963): Excessive delay in blankDisplay() while turning screen off: 420ms
D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954445968, nextTick: 14065, mDrawingTime: 0
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954445988, nextTick: 14045, mDrawingTime: 0
D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=4
D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherService( 1836): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:40:46
,D/WeatherService( 1836): 2 : ACTION screen on
,D/WeatherService( 1836): 2 : shouldTimeTickRegistered : false
D/WeatherService( 1836): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:40:46
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_ON
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  963): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
I/qcom_sensors_hal(  963): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  963): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
,I/[LGHome]EVENT( 1488): [Launcher.java:894:onPause()]onPause
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,I/LGImmersionVibrator(  963): Vibrator off
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qcom_sensors_hal(  963): hal_acquire_resources
D/qcom_sensors_hal(  963): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  963): hal_smgr_report_delete: handle=0
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/qcom_sensors_hal(  963): hal_wait_for_response: timeout=1000
D/WifiStateMachine(  963): handleScreenStateChanged: false
D/WifiStateMachine(  963): handleMessage: E msg.what=131154
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): handleMessage: X
I/[LGHome]EVENT( 1488): [Launcher.java:4955:onStop()]onStop
D/WifiStateMachine(  963): handleMessage: E msg.what=131158
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
D/WifiStateMachine(  963): processMsg: ConnectModeState
D/WifiStateMachine(  963): processMsg: DriverStartedState
D/WifiStateMachine(  963): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  963): doBoolean: DRIVER SETSUSPENDMODE 1
V/qcom_sensors_hal(  963): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  963): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  963): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  963): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
D/KeyguardViewManager( 1143): onScreenTurnedOff()
D/wpa_supplicant( 2023): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2023): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
D/WifiController(  963): CMD_SCREEN_OFF 
D/WifiController(  963): shouldWifiStayAwake TRUE
,V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{42d10538 u0 com.lge.launcher2/.Launcher t1} (stop complete)
E/AudioSystem(  963): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 963
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1157): clear
D/wpa_supplicant( 2023): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  963):    returned true
D/WifiStateMachine(  963): handleMessage: X
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1473): setPowerMode; state=2
D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
,E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
E/Parcel  (  471): Reading a NULL string not supported here.
,E/Parcel  (  471): Reading a NULL string not supported here.
D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  963): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/WeatherService( 1836): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:40:46
D/WeatherService( 1836): 2 : ACTION screen off
,D/WeatherService( 1836): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:40:46
,D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1448): Emergency Service
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1448): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1473): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
D/NfcService( 1473): NFC-C OFF
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  963): ACTION_SCREEN_OFF
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1461): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 275 plugged : true isCharging : false
D/HeadsetStateMachine( 1220): Disconnected process message: 10
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  963): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
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
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
D/WifiStateMachine(  963): processMsg: ConnectedState
D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 274 plugged : true isCharging : false
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Sensors (  448): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  963): handleMessage: E msg.what=131155
,D/WifiStateMachine(  963): processMsg: ConnectedState
,D/WifiStateMachine(  963): processMsg: L2ConnectedState
,D/WifiStateMachine(  963): handleMessage: X
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954454069155618; DSPS: 4950735; Offset: 1451954302984713480
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/VacuumService( 1555): Vacuum at: now=1451954454772 tag=VacuumService
,I/GoogleURLConnFactory( 1555): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1555): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1555): No account for auth token provided
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  963): GC_EXPLICIT freed 2899K, 47% free 30731K/57352K, paused 4ms+14ms, total 183ms
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1555): No account for auth token provided
,W/Uploader( 1555):  no longer exists, so no auth token.
,W/Uploader( 1555): No account for auth token provided
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954460037, nextTick: 59984, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954460046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954474070507101; DSPS: 5606140; Offset: 1451954302984691672
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954494071863154; DSPS: 6261544; Offset: 1451954302984704951
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954514073353594; DSPS: 6916953; Offset: 1451954302984700030
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954520030, nextTick: 59998, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954520058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954534074264088; DSPS: 7572343; Offset: 1451954302984694997
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954554075621780; DSPS: 8227747; Offset: 1451954302984709915
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954574076938151; DSPS: 8883150; Offset: 1451954302984714030
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954580043, nextTick: 59969, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954580056, nextTick: 59977, mDrawingTime: 0
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  963): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 270 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954594077847385; DSPS: 9538540; Offset: 1451954302984707737
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954614078296181; DSPS: 10193915; Offset: 1451954302984698769
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 7 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 3 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 8 BSSID 44:e9:dd:10:c0:ac SSID 'FunBox2-C0AB' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 6 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 4 BSSID dc:4a:3e:0f:c2:f1 SSID 'DIRECT-AD-HP DeskJet 3630 series' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 9 BSSID 10:9a:dd:8e:22:d9 SSID 'Apple AirPort' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2023): wlan0: BSS: Remove id 10 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2023): wlan0: BSS: Remove id 11 BSSID 06:7c:34:38:27:cc SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2023): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 64:7c:34:12:7f:81]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 44:e9:dd:10:c0:ac]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 38:f8:89:11:e9:11]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 dc:4a:3e:0f:c2:f1]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 10:9a:dd:8e:22:d9]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 64:7c:34:38:27:cc]
,D/WifiMonitor(  963): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 06:7c:34:38:27:cc]
,D/dalvikvm( 2663): GC_CONCURRENT freed 7742K, 32% free 16891K/24836K, paused 3ms+2ms, total 51ms
,D/dalvikvm( 2663): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954634079166466; DSPS: 10849303; Offset: 1451954302984714562
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954640039, nextTick: 59968, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954640054, nextTick: 59979, mDrawingTime: 0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  963): updateLightListLocked :r=NotificationRecord(0x450317f8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  963): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,D/dalvikvm( 1555): GC_CONCURRENT freed 1762K, 27% free 18134K/24836K, paused 7ms+7ms, total 77ms
,D/dalvikvm( 1555): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 1555): WAIT_FOR_CONCURRENT_GC blocked 33ms
,W/GLSActivity( 1555): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1555): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1555): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1555): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1555): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1555): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4401): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4401): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4401): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4401): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4401): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4401): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4401): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4401): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4401): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4401): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LocationManagerService(  963): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  963): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/LocationManagerService(  963): remove 42df6bc0
,D/dalvikvm( 2663): GC_CONCURRENT freed 1829K, 32% free 17054K/24836K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2663): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2663): GC_CONCURRENT freed 1731K, 31% free 17259K/24836K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 2663): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/Mlt MonitorService( 2663): parseLastkmsg to dump
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954654079626209; DSPS: 11504678; Offset: 1451954302984716542
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954674083278851; DSPS: 12160158; Offset: 1451954302984707074
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954694083719443; DSPS: 12815532; Offset: 1451954302984720420
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954700034, nextTick: 59991, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954700046, nextTick: 59986, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954714084180670; DSPS: 13470907; Offset: 1451954302984723883
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954734087537901; DSPS: 14126378; Offset: 1451954302984693663
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954754088412054; DSPS: 14781766; Offset: 1451954302984713324
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954760039, nextTick: 59967, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954760055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954774088870151; DSPS: 15437141; Offset: 1451954302984713657
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954794089304700; DSPS: 16092515; Offset: 1451954302984720960
,D/dalvikvm( 2663): GC_CONCURRENT freed 2453K, 33% free 16726K/24836K, paused 10ms+1ms, total 62ms
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954814089766321; DSPS: 16747891; Offset: 1451954302984694300
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954820033, nextTick: 59990, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954820056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954834091154626; DSPS: 17403296; Offset: 1451954302984709314
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954854093006657; DSPS: 18058717; Offset: 1451954302984699773
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954874093436420; DSPS: 18714091; Offset: 1451954302984702290
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954880064, nextTick: 59964, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954880065, nextTick: 59967, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954894094806014; DSPS: 19369496; Offset: 1451954302984698593
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954914096089069; DSPS: 20024898; Offset: 1451954302984699909
,I/ActivityManager(  963): Killing 4707:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954934096989475; DSPS: 20680287; Offset: 1451954302984715306
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954940076, nextTick: 59945, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451954940085, nextTick: 59947, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954954098379950; DSPS: 21335693; Offset: 1451954302984701972
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954974099661532; DSPS: 21991095; Offset: 1451954302984701816
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451954994100560114; DSPS: 22646484; Offset: 1451954302984715388
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955000054, nextTick: 59975, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955000055, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955014101926201; DSPS: 23301889; Offset: 1451954302984708184
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955034103876796; DSPS: 23957313; Offset: 1451954302984705654
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955054105300985; DSPS: 24612720; Offset: 1451954302984695517
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955060049, nextTick: 59980, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955060055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955074106682384; DSPS: 25268125; Offset: 1451954302984703625
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955094107958620; DSPS: 25923527; Offset: 1451954302984698122
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955114109258869; DSPS: 26578929; Offset: 1451954302984716633
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955120047, nextTick: 59982, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955120057, nextTick: 59976, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955134110694769; DSPS: 27234336; Offset: 1451954302984718207
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/QcConnectivityService(  963): Setting timer for 720seconds
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955154112030390; DSPS: 27889740; Offset: 1451954302984711055
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955174112921591; DSPS: 28545129; Offset: 1451954302984717246
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955180040, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955180054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955194114309681; DSPS: 29200535; Offset: 1451954302984701527
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955214115602973; DSPS: 29855937; Offset: 1451954302984713081
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955234116491104; DSPS: 30511326; Offset: 1451954302984716202
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955240030, nextTick: 59998, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955240049, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955254117853134; DSPS: 31166731; Offset: 1451954302984704941
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955274119191375; DSPS: 31822135; Offset: 1451954302984700409
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955294119621634; DSPS: 32477509; Offset: 1451954302984703422
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955300044, nextTick: 59981, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955300048, nextTick: 59984, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955314121022432; DSPS: 33132915; Offset: 1451954302984700411
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955334122945319; DSPS: 33788338; Offset: 1451954302984700691
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955354123381782; DSPS: 34443712; Offset: 1451954302984709907
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955360054, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955360055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955374124769709; DSPS: 35099118; Offset: 1451954302984694026
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955394126041631; DSPS: 35754519; Offset: 1451954302984714727
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955414126943277; DSPS: 36409909; Offset: 1451954302984700846
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955420050, nextTick: 59976, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955420054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955434128321479; DSPS: 37065314; Offset: 1451954302984705757
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955454129602170; DSPS: 37720716; Offset: 1451954302984704710
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955474130058165; DSPS: 38376091; Offset: 1451954302984702941
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955480041, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955480054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955494131455427; DSPS: 39031497; Offset: 1451954302984696394
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955514133375541; DSPS: 39686920; Offset: 1451954302984693901
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955534133804596; DSPS: 40342294; Offset: 1451954302984695710
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955540049, nextTick: 59977, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955540051, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955554135207209; DSPS: 40997700; Offset: 1451954302984694514
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  963): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 259 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1220): Disconnected process message: 10
,W/Settings(  963): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  963): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1461): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1461): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1461): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1461): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955574136554001; DSPS: 41653104; Offset: 1451954302984698533
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955594137876601; DSPS: 42308507; Offset: 1451954302984708877
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955600035, nextTick: 59987, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955600041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955614138331727; DSPS: 42963882; Offset: 1451954302984706239
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955634139618907; DSPS: 43619284; Offset: 1451954302984711681
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955654140051436; DSPS: 44274658; Offset: 1451954302984716964
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955660043, nextTick: 59970, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955660055, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955674140506837; DSPS: 44930033; Offset: 1451954302984714601
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955694141403805; DSPS: 45585423; Offset: 1451954302984696042
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955714141836855; DSPS: 46240797; Offset: 1451954302984701846
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955720050, nextTick: 59970, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955720056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955734143388701; DSPS: 46896208; Offset: 1451954302984697295
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955754144312049; DSPS: 47551598; Offset: 1451954302984705116
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955774145196479; DSPS: 48206987; Offset: 1451954302984704536
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955780043, nextTick: 59975, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955780052, nextTick: 59978, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955794146516568; DSPS: 48862390; Offset: 1451954302984712369
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955814147375120; DSPS: 49517778; Offset: 1451954302984716429
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955834147829296; DSPS: 50173153; Offset: 1451954302984712841
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955840039, nextTick: 59968, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955840054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955854148731254; DSPS: 50828543; Offset: 1451954302984699272
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  963): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  963): Done.
,D/QcConnectivityService(  963): Setting timer for 720seconds
,D/GCM     ( 1555): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  963): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  963): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955874149592094; DSPS: 51483931; Offset: 1451954302984705620
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955894150058658; DSPS: 52139306; Offset: 1451954302984714420
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955900032, nextTick: 59990, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955900054, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955914150512264; DSPS: 52794681; Offset: 1451954302984710263
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955934151806373; DSPS: 53450083; Offset: 1451954302984722633
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955954152238972; DSPS: 54105458; Offset: 1451954302984697469
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955960048, nextTick: 59979, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451955960051, nextTick: 59981, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955974153608451; DSPS: 54760863; Offset: 1451954302984693657
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451955994154459147; DSPS: 55416251; Offset: 1451954302984689860
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956014155301776; DSPS: 56071638; Offset: 1451954302984708515
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956020048, nextTick: 59979, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956020053, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956034155771777; DSPS: 56727013; Offset: 1451954302984720752
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956054156632663; DSPS: 57382402; Offset: 1451954302984696628
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956074157060555; DSPS: 58037776; Offset: 1451954302984697274
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956080038, nextTick: 59970, mDrawingTime: 9
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956080054, nextTick: 59979, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956094157956919; DSPS: 58693165; Offset: 1451954302984708628
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956114158856280; DSPS: 59348555; Offset: 1451954302984692462
,I/ProcessStatsService(  963): Prepared write state in 22ms
,I/ProcessStatsService(  963): Prepared write state in 24ms
,D/LocationManagerService(  963): getAllProviders()=[passive, gps, network]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/EventLogService( 1965): Aggregate from 1451954428526 (log), 1451954331332 (data)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/GLSUser ( 1555): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1555): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1555): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1555): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1555): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1555): [DefaultAuthDelegateService] Use browser flow? false
,I/ProcessStatsService(  963): Pruning old procstats: /data/system/procstats/state-2016-01-04-03-07-14.bin
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956134160218281; DSPS: 60003959; Offset: 1451954302984711690
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956140049, nextTick: 59969, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956140056, nextTick: 59977, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956154161548465; DSPS: 60659363; Offset: 1451954302984699100
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956174161995857; DSPS: 61314737; Offset: 1451954302984719246
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956194163591149; DSPS: 61970150; Offset: 1451954302984697107
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956200051, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1451956200055, nextTick: 59978, mDrawingTime: 0
,D/qcom_sensors_hal(  963): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  963): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  963): hal_ts_offset_is: Apps: 1451956214164501986; DSPS: 62625540; Offset: 1451954302984692416
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7139): 
D/AndroidRuntime( 7139): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7139): CheckJNI is OFF
D/dalvikvm( 7139): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7139): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7139): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7139): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7139): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 7139): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 7139): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7139): failed to load memtrack module: -2
D/AndroidRuntime( 7139): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  963): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
W/PackageSettings(  963): Skipping PackageSetting{42d6e6b8 com.example.hello/10312} due to missing metadata
I/ActivityManager(  963): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/dalvikvm( 1488): GC_EXPLICIT freed 3926K, 14% free 60358K/69868K, paused 2ms+4ms, total 33ms
D/dalvikvm( 2680): GC_EXPLICIT freed 4678K, 27% free 18178K/24836K, paused 2ms+2ms, total 29ms
D/KeyguardModel( 1143): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1488): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/InputReader(  963): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
E/SlideAside( 3740): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
D/AppUp4:Utils( 4332): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 4332): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3740): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
I/ActivityManager(  963): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7157 uid=10090 gids={50090}
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "smsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/System.err( 2663): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "mms"
W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/AppUp4  ( 4332):  isExcludedPackage  packagename = com.test.thalitest
W/System.err( 2663): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2663): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2663): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2663): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2663): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2663): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2663): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2663): 	at java.lang.reflect.Method.invokeNative(Native Method)
D/HyLog   ( 7157): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7157): I : /data/font/config/dfactpre.dat, No such file or directory (2)
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
D/HyLog   ( 7157): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "mmsto"
W/ActivityManager(  963): getAssistContextExtras failed: no resumed activity
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/GeofencerStateMachine( 1423): Ignoring removeGeofence because network location is disabled.
W/System.err( 2663): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2663): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2663): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2663): 	at dalvik.system.NativeStart.main(Native Method)
D/AppUp4  ( 4332):  isExcludedPackage TRUE : com.test.thalitest
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1143): changeTargets() succeeded. size: 20
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "sms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  963): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7183 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "smsto"
D/KeyguardModel( 1143): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/LockScreenSettings( 7157): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  963): GC_EXPLICIT freed 3310K, 47% free 30746K/57352K, paused 4ms+9ms, total 133ms
D/dalvikvm(  963): WAIT_FOR_CONCURRENT_GC blocked 12ms
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "mms"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/KeyguardModel( 1143): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1143): createShortcutInfo...
I/PackageManager(  963):   Action: "android.intent.action.SENDTO"
I/PackageManager(  963):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  963):   Scheme: "mmsto"
I/PackageManager(  963): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/administrator(  963): Handling package changes for user 0
D/HyLog   ( 7183): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7183): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7183): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1143): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1143): createShortcutInfo...
D/[BNRAppListMgrReceiver]( 7183): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
D/KeyguardModel( 1143): handleShortcutListChanged...
I/ActivityManager(  963): Killing 4966:com.google.android.setupwizard/u0a52 (adj 15): empty #17
I/ActivityManager(  963): Killing 4986:com.android.chrome/u0a63 (adj 15): empty #17
D/KeyguardModel( 1143): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1143): createShortcutInfo...
D/KeyguardModel( 1143): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1143): createShortcutInfo...
D/VoicemailCleanupService( 1800): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  963): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7197 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/KeyguardModel( 1143): handleShortcutListChanged...
D/HyLog   ( 7197): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7197): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7197): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/BackupManagerService(  963): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  963): updateIntentFilterConfig
I/InteractionManagerConfigurator(  963): com.test.thalitest isn't inclued in dragdropPackageList
V/BackupManagerService(  963): removePackageParticipantsLocked: uid=10304 #1
I/LGEmail ( 7197): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/LGEmail ( 7197): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
D/dalvikvm(  963): GC_EXPLICIT freed 519K, 47% free 30670K/57352K, paused 4ms+15ms, total 172ms
I/[LGHome]EVENT( 1488): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/BaseRuntimeLoader( 7197): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7197): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7197): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 7197): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/PackageChangeReceiver( 7197): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/PackageIntentReceiver( 2611): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2611): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2611): Delete mPackageMame : com.test.thalitest
I/IcingCorporaProvider( 2680): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  963): Killing 5017:com.lge.drmservice/u0a66 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
D/AndroidRuntime( 7139): Shutting down VM
I/ActivityManager(  963): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7215 uid=10073 gids={50073, 3003, 1028, 1015}
D/dalvikvm( 7139): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 1ms+1ms, total 3ms
D/HyLog   ( 7215): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 7215): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 7215): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  963): Killing 5076:com.google.android.apps.magazines/u0a104 (adj 15): empty for 1800s
I/ActivityManager(  963): Killing 5061:com.lge.wireless_storage/u0a101 (adj 15): empty for 1800s
I/ActivityManager(  963): Killing 5038:com.lge.lgdmsgcm/1000 (adj 15): empty for 1800s
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused
I/IcingCorporaProvider( 2680): UpdateCorporaTask done [took 78 ms] updated apps [took 78 ms] 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/SQLiteDatabase( 7215): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 7215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 7215): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7215): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 7215): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 7215): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 7215): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 7215): 	at aJh.a(Scopes.java:65)
E/SQLiteDatabase( 7215): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 7215): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteDatabase( 7215): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteDatabase( 7215): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 7215): 	at aGr.a(GellyInjector.java:117)
E/SQLiteDatabase( 7215): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteDatabase( 7215): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 7215): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteDatabase( 7215): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteDatabase( 7215): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 7215): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 7215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7215): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 7215): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 7215): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7215): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7215): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 7215): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 7215): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7215): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 7215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 7215): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7215): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 7215): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 7215): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 7215): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 7215): 	at aJh.a(Scopes.java:65)
E/SQLiteOpenHelper( 7215): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 7215): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteOpenHelper( 7215): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteOpenHelper( 7215): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 7215): 	at aGr.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 7215): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 7215): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 7215): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteOpenHelper( 7215): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteOpenHelper( 7215): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 7215): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 7215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7215): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 7215): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 7215): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7215): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7215): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 7215): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 7215): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7215): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 7215): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 7215): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7215): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 7215): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 7215): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 7215): 	at azE.a(Suppliers.java:125)
E/SQLiteDatabase( 7215): 	at ahj.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 7215): threadid=11: thread exiting with uncaught exception (group=0x4186ae48)
I/Process ( 7215): Sending signal. PID: 7215 SIG: 9
E/AndroidRuntime( 7215): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 7215): Process: com.google.android.apps.docs, PID: 7215
E/AndroidRuntime( 7215): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7215): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 7215): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7215): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7215): 	at ahn.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 7215): 	at ahi.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 7215): 	at ahi.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 7215): 	at azE.a(Suppliers.java:125)
E/AndroidRuntime( 7215): 	at ahj.run(AbstractDatabaseInstance.java:455)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/DropBoxManagerService(  963): Can't write: system_app_crash
E/DropBoxManagerService(  963): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  963): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  963): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  963): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  963): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  963): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  963): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  963): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  963): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  963): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  963): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  963): 	... 5 more
E/SQLiteLog( 2663): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2663): Error inserting f006=-1 f003= f002=1451956233320 f005=7215 f004=20
E/SQLiteDatabase( 2663): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2663): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2663): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2663): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2663): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2663): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2663): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)
I/ActivityManager(  963): Process com.google.android.apps.docs (pid 7215) has died.
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c88ee0 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Going to sleep and all paused

```
