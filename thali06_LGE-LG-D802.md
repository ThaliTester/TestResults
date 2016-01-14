#### Test 55613145c131883_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4616): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  968): Killing 3608:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1965): GC_CONCURRENT freed 1615K, 22% free 19437K/24832K, paused 4ms+4ms, total 36ms
D/dalvikvm( 1965): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/ConfigFetchService( 1965): fetch service done; releasing wakelock
I/ConfigFetchService( 1965): stopping self
D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1965): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4659): 
D/AndroidRuntime( 4659): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4659): CheckJNI is OFF
D/dalvikvm( 4659): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4659): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4659): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4659): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4659): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2035): nl80211: survey data missing!
D/WifiStateMachine(  968): handleMessage: X
D/dalvikvm( 4659): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1965): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1965): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1965): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/memtrack( 4659): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4659): failed to load memtrack module: -2
D/AndroidRuntime( 4659): Calling main entry com.android.commands.am.Am
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4659
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (133 us)
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  968): resumeTopActivityLocked: Pausing null
V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  968): setFocusedStack: mFocusedStack=ActivityStack{435b6228 stackId=1, 2 tasks}
I/ActivityManager(  968): startService SlideAside
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/UsbSettingsControl( 2613): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2613): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4659): Shutting down VM
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Restarting ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
D/dalvikvm( 4659): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4677 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3773): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/SlideAside( 3773): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3773): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4677): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4677): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4677): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  968): battery changed pluggedType: 2
V/WebViewChromium( 4677): Binding Chromium to the background looper Looper (main, tid 1) {42abbb78}
I/chromium( 4677): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4677): Initializing chromium process, renderers=0
W/chromium( 4677): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4677): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4677): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4677): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4677): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4677): Remote Branch: 
I/Adreno-EGL( 4677): Local Patches: 
I/Adreno-EGL( 4677): Reconstruct Branch: 
I/dalvikvm( 4677): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4677): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4677): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4677): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4677): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4677): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4677): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4677): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4677): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4677): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4677): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4677): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4677): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4677): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4677): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4677): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4677): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4677): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4677): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4677): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,W/BaseRuntimeLoader( 4677): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4677): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4677): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4677): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4677): Enabling debug mode 0
W/AwContents( 4677): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  968): IME STATUS OFF
W/AwContents( 4677): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +338ms
I/ActivityManager( 4677): Timeline: Activity_idle id: android.os.BinderProxy@42abd348 time:109234
D/JsMessageQueue( 4677): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4677): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42ac18e0
D/dalvikvm( 4677): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42ac18e0
D/jxcore_app_log( 4677): JniHelper::setJavaVM(0x41a72808), pthread_self() = 1639320440
D/JX-Cordova( 4677): jxcore cordova android initializing
I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3} time:109651
D/UsbSettings( 2613): [AUTORUN] onStop()
D/ActivityManager(  968): no-history finish of ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  968): Finishing activity token=Token{435155c0 ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
D/dalvikvm( 4677): GC_CONCURRENT freed 2779K, 12% free 21869K/24832K, paused 2ms+3ms, total 55ms
D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 113K, 12% free 21866K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 125K, 12% free 21886K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 23.638MB for 95956-byte allocation
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 179K, 13% free 21920K/24928K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 23.717MB for 143930-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 252K, 13% free 21968K/25072K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 23.832MB for 215890-byte allocation
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 368K, 13% free 22042K/25284K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 24.007MB for 323830-byte allocation
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 565K, 14% free 22162K/25604K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 24.280MB for 485740-byte allocation
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 862K, 15% free 22338K/26080K, paused 30ms, total 30ms
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 1280K, 14% free 22594K/26080K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 25.280MB for 1092904-byte allocation
,D/dalvikvm( 4677): GC_CONCURRENT freed 1822K, 16% free 22984K/27148K, paused 2ms+3ms, total 38ms
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 237K, 16% free 22902K/27148K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 26.102MB for 1639352-byte allocation
,D/dalvikvm( 4677): GC_CONCURRENT freed 1768K, 19% free 23561K/28752K, paused 1ms+3ms, total 47ms
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 1228K, 19% free 23543K/28752K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 27.509MB for 2459024-byte allocation
,D/dalvikvm( 4677): GC_CONCURRENT freed 318K, 18% free 25851K/31156K, paused 2ms+2ms, total 39ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 4301K, 22% free 24542K/31156K, paused 32ms, total 32ms
,I/dalvikvm-heap( 4677): Grow heap (frag case) to 29.658MB for 3688532-byte allocation
,D/dalvikvm( 4677): GC_CONCURRENT freed 327K, 20% free 28019K/34760K, paused 3ms+6ms, total 46ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 4677): GC_FOR_ALLOC freed 3284K, 27% free 25496K/34760K, paused 24ms, total 25ms
,W/jxcore-log( 4677): Initializing JXcore engine
,W/jxcore-log( 4677): JXcore engine is ready
,D/dalvikvm( 4677): GC_CONCURRENT freed 338K, 20% free 28151K/34760K, paused 3ms+1ms, total 45ms
,D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 35ms
,W/jxcore-log( 4677): Starting JXcore engine
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/jxcore-log( 4677): Platform android
W/jxcore-log( 4677): 
,W/jxcore-log( 4677): Process ARCH arm
W/jxcore-log( 4677): 
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,I/jxcore-log( 4677): JXcore Cordova bridge is ready!
I/jxcore-log( 4677): 
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,W/jxcore-log( 4677): JXcore engine is started
,I/chromium( 4677): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/WifiController(  968): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/WifiController(  968): battery changed pluggedType: 2
I/chromium( 4677): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4677): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.450806 Y: -0.398804 Z: 9.788864 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450806 .y:-0.398804 .z:9.788864
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.447510 Y: -0.399963 Z: 9.801636 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.447510 .y:-0.399963 .z:9.801636
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
I/jxcore-log( 4677): Toggling radios to true
I/jxcore-log( 4677): 
D/BluetoothManagerService(  968): Message: 20
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44ce1d88:true
,D/BluetoothAdapter( 4677): enable(): BT is already enabled..!
,D/WifiStateMachine(  968): handleMessage: E msg.what=131145
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doBoolean: DISCONNECT
D/WifiService(  968): New client listening to asynchronous messages
D/WifiService(  968): setWifiEnabled: true pid=4677, uid=10304
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  968): setWifiEnabled startWifiDelaySendMsg true
D/WifiService(  968): disconnect pid=4677, uid=10304
,D/WifiService(  968): reconnect pid=4677, uid=10304
I/jxcore-log( 4677): Radios toggled
I/jxcore-log( 4677): 
I/jxcore-log( 4677): My device name is: LGE-LG-D802
I/jxcore-log( 4677): 
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=10): 44 49 53 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2035): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 2035): wlan0: Cancelling scan request
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2035): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2035): TDLS: Tear down peers
D/wpa_supplicant( 2035): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 2035): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2035): wlan0: Deauthentication notification
D/wpa_supplicant( 2035): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2035): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2035): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2035): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2035): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 2035): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb83c0d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2035):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2035): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 2035): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: ConnectedState
W/Settings(  968): Setting airp,lane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectingState
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131146
D/WifiStateMachine(  968): processMsg: DisconnectingState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiNative-wlan0(  968): doBoolean: RECONNECT
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 2035): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 2035): Fast associate: Old scan results
D/wpa_supplicant( 2035): wlan0: Setting scan request: 0 sec 0 usec
D/wpa_supplicant( 2035): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 2035): wlan0: nl80211: scan request
D/wpa_supplicant( 2035): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 2035): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 2035): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147460
D/WifiStateMachine(  968): processMsg: DisconnectingState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): Network connection lost
D/WifiStateMachine(  968): Stopping DHCP and clearing IP
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2035): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2035): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2035): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
,D/DhcpStateMachine(  968): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  968): addressRemoved: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 0
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/WifiHS20(  968): hidePasspointNotification off =false
D/QcConnectivityService(  968): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
D/QCNEA   (  424): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  424): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  424): |CAC| updateNetCfgInfo
V/QCNEA   (  424): |CAC| *********************************************
V/QCNEA   (  424): |CAC|                   Netconfig               
V/QCNEA   (  424): |CAC| *********************************************
V/QCNEA   (  424): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  424): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  424): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  424): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  424): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  424): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  424): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  424): |CAC| *********************************************
D/QCNEA   (  424): |CAC| Received bssid= 
D/QCNEA   (  424): |CAC| net type = 3
V/QCNEA   (  424): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  424): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  424): |CAC| 	ssid           =NG700
V/QCNEA   (  424): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  424): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  424): |CAC| *********************************************
D/QCNEA   (  424): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  424): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  424): |CAC| dispatchNetCfg: updating:0xb81bc8dc
D/QCNEA   (  424): |CAC| readCallback: read len:0, ret:-1, errno:11
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
D/QcConnectivityService(  968): Attempting to switch to mobile
D/QcConnectivityService(  968): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  968): handleConnectivityChange: preConnState=1 connState=2
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=DisconnectedState
D/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
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
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  968): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
V/        (  264): RouteController
I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4740 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4740): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  264): RouteController
V/        (  264): RouteController
V/        (  264): RouteController
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
D/NetUtils(  968): android_net_utils_resetConnections in env=0x5c83c690 clazz=0x6b100001 iface=wlan0 mask=0x3
I/PCSuite ( 4740): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/QcConnectivityService(  968): resetConnections(wlan0, 3)
D/PCSuite ( 4740): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4740): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/NativeCrypto( 1558): Read error: ssl=0x63af4160: I/O error during system call, Connection timed out
V/NativeCrypto( 1558): SSL shutdown failed: ssl=0x63af4160: I/O error during system call, Broken pipe
I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4775 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
I/ActivityManager(  968): Killing 4192:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4775): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4775): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4775): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/LocSvc_java(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
D/GpsLocationProvider(  968): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=false
D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 4775): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4775): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4775): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4775): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4775): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4775): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4775): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 4775): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4775): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
I/ActivityManager(  968): Killing 2146:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
D/DhcpStateMachine(  968): StoppedState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ProcessCpuTracker(  968): Skipping unknown process pid 4768
W/ProcessCpuTracker(  968): Skipping unknown process pid 4769
W/ProcessCpuTracker(  968): Skipping unknown process pid 4771
W/ProcessCpuTracker(  968): Skipping unknown process pid 4792
I/GAV2    ( 4616): Thread[GAThread,5,main]: No campaign data found.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/ConfigService( 1558): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/CaptivePortalTracker(  968): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Tethering(  968): MasterInitialState.processMessage what=3
D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
,D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42ada510
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3018): start selecting data
,D/SIMObserver( 3018): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4045): begin check event
,I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity
,I/ActivityManager(  968): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4804 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/HyLog   ( 4804): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 2035): wlan0: nl80211: New scan results available
D/wpa_supplicant( 2035): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 2035): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 2035): nl80211: Survey data missing
D/wpa_supplicant( 2035): wlan0: BSS: Start scan result update 2
D/wpa_supplicant( 2035): wlan0: BSS: Add new id 10 BSSID 64:7c:34:38:27:cc SSID 'UPC0990019'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 2035): wlan0: New scan results available
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2035): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2035): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 2035): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 2035): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 2035): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 2035): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2035): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 2035): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 2035): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[4] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): WPS: AP[5] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 2035): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 2035): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 2035): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2035): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-50
D/wpa_supplicant( 2035): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 2035): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-56 wps
D/wpa_supplicant( 2035): wlan0:    selected based on RSN IE
D/wpa_supplicant( 2035): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg_mdm_auto_connect_policy 1
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2035): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83c25a8  current_ssid=0x0
D/wpa_supplicant( 2035): scard is not null..
D/wpa_supplicant( 2035): wlan0: [Events.c:1455]Request association: reassociate: 1  selected: c0:ff:d4:d3:aa:,48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 2035): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2035): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 2035): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 2035): wlan0: Cancelling scan request
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2035): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 2035): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 2035): RSN: PMKSA cache search - network_ctx=0xb83c25a8 try_opportunistic=0
D/wpa_supplicant( 2035): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): RSN: No PMKSA cache entry found
D/wpa_supplicant( 2035): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 2035): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 2035): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2035): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 2035): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 2035): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 2035): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 2035): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 2035): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2035): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 2035): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2035): nl80211: Unsubscribe mgmt frames handle 0xb83c1590 (mode change)
D/wpa_supplicant( 2035): nl80211: Subscribe to mgmt frames with non-AP handle 0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 2035): nl80211: Register frame type=0xd0 nl_handle=0xb83c1590
D/wpa_supplicant( 2035): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 2035): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 2035):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035):   * freq=2412
D/wpa_supplicant( 2035):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 2035):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035):   * Auth Type 0
D/wpa_supplicant( 2035):   * WPA Versions 0x2
D/wpa_supplicant( 2035): nl80211: Connect request send successfully
D/wpa_supplicant( 2035): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2035): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 64:7c:34:38:27:cc]
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/HyLog   ( 4804): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4804): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WifiStateMachine(  968): handleMessage: E msg.what=147461
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  968): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 2035): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 2035): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2035): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 2035): WPS: Unknown Vendor Extension (Vendor ID 311)
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 2035): nl80211: Event message available
D/wpa_supplicant( 2035): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 2035): nl80211: Connect event
D/wpa_supplicant( 2035): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 2035): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 2035): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 2035): wlan0: Association info event
D/wpa_supplicant( 2035): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 2035): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 2035): wlan0: freq=2412 MHz
D/wpa_supplicant( 2035): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2035): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 2035): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 2035): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 2035): scard is not null..
D/wpa_supplicant( 2035): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 2035): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 2035): TDLS: Remove peers on association
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 2035): EAPOL: enable timer tick
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2035): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2035): wlan0: Cancelling scan request
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
W/WifiMonitor(  968): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 2035): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 27 11 42 8e e6 96 db 15 81 d6 db 2a e9 5d c5 ...
D/wpa_supplicant( 2035): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 2035): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 2035): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2035): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
V/DownloadManager( 4804): DownloadService onCreate
D/wpa_supplicant( 2035): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 2035):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2035):   key_nonce - hexdump(len=32): 27 11 42 8e e6 96 db 15 81 d6 db 2a e9 5d c5 a3 6d 90 dc 18 4a 65 1c d2 1d 34 e4 51 de cc 79 9d
D/wpa_supplicant( 2035):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 27 11 42 8e e6 96 db 15 81 d6 db 2a e9 5d c5 ...
D/wpa_supplicant( 2035): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2035): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 2035): Get randomness: len=32 entropy=10
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/wpa_supplicant( 2035): WPA: Renewed SNonce - hexdump(len=32): 14 e9 ca 72 81 2c e4 58 a4 ae 01 c1 4e 2b ab 97 49 f9 6e da 1b bf ea 6a 0f f5 a3 11 65 a1 00 7a
D/wpa_supplicant( 2035): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): WPA: Nonce1 - hexdump(len=32): 14 e9 ca 72 81 2c e4 58 a4 ae 01 c1 4e 2b ab 97 49 f9 6e da 1b bf ea 6a 0f f5 a3 11 65 a1 00 7a
D/wpa_supplicant( 2035): WPA: Nonce2 - hexdump(len=32): 27 11 42 8e e6 96 db 15 81 d6 db 2a e9 5d c5 a3 6d 90 dc 18 4a 65 1c d2 1d 34 e4 51 de cc 79 9d
D/wpa_supplicant( 2035): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 2035): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2035): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 2035): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 2035): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2035): WPA: Derived Key MIC - hexdump(len=16): 4c cf c5 b2 40 09 03 b5 d0 b0 8a 23 27 22 f3 45
D/wpa_supplicant( 2035): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 14 e9 ca 72 81 2c e4 58 a4 ae 01 c1 4e 2b ab ...
D/EAS     ( 4598): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4598): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
I/DownloadManager( 4804): in removeSpuriousFiles
,D/eas_req ( 4598): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 4804): DownloadService onStartCommand
D/wpa_supplicant( 2035): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 27 11 42 8e e6 96 db 15 81 d6 db 2a e9 5d c5 ...
D/wpa_supplicant( 2035): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 2035): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 2035): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 2035): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 2035):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 2035):   key_nonce - hexdump(len=32): 27 11 42 8e e6 96 db 15 81 d6 db 2a e9 5d c5 a3 6d 90 dc 18 4a 65 1c d2 1d 34 e4 51 de cc 79 9d
D/wpa_supplicant( 2035):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_rsc - hexdump(len=8): 12 05 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 2035):   key_mic - hexdump(len=16): d1 4a 21 fb 47 dc 12 9e 10 b4 e6 1c 67 68 9f 7b
D/wpa_supplicant( 2035): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 27 11 42 8e e6 96 db 15 81 d6 db 2a e9 5d c5 ...
D/wpa_supplicant( 2035): RSN: encrypted key data - hexdump(len=56): 16 27 88 8f 69 53 68 56 2d 9e ec 46 e6 0c ca 61 2c a3 3c 9a 58 4c fb a0 b2 87 62 12 15 ba dd 2e ...
D/wpa_supplicant( 2035): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 2035): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 2035): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 2035): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 a6 39 ...
D/wpa_supplicant( 2035): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 2035): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 2035): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 2035): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2035): WPA: Derived Key MIC - hexdump(len=16): 1d 2a 6a 2b 0f 99 94 88 73 84 ef 9c 4b 68 b1 d2
D/wpa_supplicant( 2035): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 2035): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb83c1c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 2035):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2035): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 2035): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 2035): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 2035): WPA: RSC - hexdump(len=6): 12 05 00 00 00 00
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f2503a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 2035):    broadcast key
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
I/wpa_supplicant( 2035): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 2035): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2035): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 2035): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 2035): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/wpa_supplicant( 2035): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2035): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): EAPOL: External notification - portValid=1
D/wpa_supplicant( 2035): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 2035): EAP: EAP entering state DISABLED
D/wpa_supplicant( 2035): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 2035): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 2035): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2035): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 2035): EAPOL authentication completed successfully
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: DisconnectedState
D/wpa_supplicant( 2035): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 2035): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 2035): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): Network connection established
D/WifiNative-wlan0(  968): doString: STATUS
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 2035): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0(  968):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  968): ssid=NG700
D/WifiNative-wlan0(  968): id=0
D/WifiNative-wlan0(  968): mode=station
D/WifiNative-wlan0(  968): pairwise_cipher=CCMP
D/WifiNative-wlan0(  968): group_cipher=CCMP
D/WifiNative-wlan0(  968): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  968): wpa_state=COMPLETED
D/WifiNative-wlan0(  968): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  968): address=34:fc:ef:de:0a:e2
V/DownloadManager( 4804): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/WifiServiceExtension(  968): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  968): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
I/LgeMiscReceiver( 4343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4343): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4343): networkInfo.isConnected() = false
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
D/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/DhcpStateMachine(  968): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/DhcpStateMachine(  968): WaitBeforeStartState
D/WifiStateMachine(  968): ObtainingIpState{ when=-10ms what=147462 obj=android.net.wifi.StateChangeResult@44008740 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
D/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiStateMachine(  968): processMsg: ObtainingIpState
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
D/WifiStateMachine(  968): ObtainingIpState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@451054b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=147459
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-6ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-3ms what=131155 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/WifiStateMachine(  968): processMsg: L2ConnectedState
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/wpa_supplicant( 2035): nl80211: survey data missing!
V/DownloadManager( 4804): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b02d18 on behalf of 4804
V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b04bb0 on behalf of 4804
I/DownloadManager( 4804): in trimDatabase
V/DownloadManager( 4804): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b06db0 on behalf of 4804
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196612
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-22ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
,E/Parcel  (  424): Reading a NULL string not supported here.
V/DownloadManager( 4804): DownloadService onDestroy
W/linker  ( 4598): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4598): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4598): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4598): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4598): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
D/HtmlEditor( 4598): register_HtmlEditor, Success
D/HtmlEditor( 4598): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4837 uid=10052 gids={50052, 3003}
D/HtmlEditor( 4598): register_HtmlEditorTimer, Success
D/HtmlEditor( 4598): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4598): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4598): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4598): register_HtmlEditorFont, Success
D/HtmlEditor( 4598): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4598): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4598): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4598): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4598): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4598): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4598): JNI_OnLoad Success
I/HubEmail( 4598): JNI_OnLoad()
I/HubEmail( 4598): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4598): registerNatives()
I/HubEmail( 4598): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4598): registerNativeMethods()
I/HubEmail( 4598): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
D/HyLog   ( 4837): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4837): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4837): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/Settings( 4598): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  968): Killing 3918:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
V/LGRssiData( 4837): [loadRssi] File not exist 
V/LGRssiData( 4837): [loadRssi] File not exist 
V/TelephonyAutoProfiling( 4837): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4837): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4837): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4837): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4837): [getValue] FEATURE key : vzw_roaming_state, value : null
E/PhoneMonitor( 4837): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4837): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4851 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  968): Killing 4388:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
,D/HyLog   ( 4851): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4851): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4851): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  968): doBoolean: SET ps 0
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 2035): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 2035): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 2035): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
,D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  968):    returned null
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  968): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  968):    returned null
D/DhcpStateMachine(  968): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  968): DHCP Start wake lock is acquired.
I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4864 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  968): Killing 4521:com.android.defcontainer/u0a4 (adj 15): empty #17
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43370cc8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43370cc8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  264): Setting iface cfg
D/WifiStateMachine(  968): addressUpdated: 192.168.1.145/24 on wlan0 flags 128 scope 0
D/CommandListener(  264): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  968): setInterfaceUpWithDhcpInfo: IP configuration succeeded: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-4ms what=131212 obj=192.168.1.145/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiStateMachine(  968): processMsg: DefaultState
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=196613
D/WifiStateMachine(  968): processMsg: ObtainingIpState
D/WifiStateMachine(  968): ObtainingIpState{ when=-4ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  968): doBoolean: SET ps 1
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2035): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2035): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 2035): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  968):    returned true
D/WifiNative-wlan0(  968): doBoolean: DRIVER BTCOEXMODE 2
,D/HyLog   ( 4864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4864): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4864): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  968):    returned true
,D/WifiStateMachine(  968): DHCP successful
D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  968): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  968): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState enter
,D/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
,E/Parcel  (  424): Reading a NULL string not supported here.
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=135190
D/WifiStateMachine(  968): processMsg: VerifyingLinkState
D/WifiStateMachine(  968): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  968): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  968): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState enter
,D/WifiStateMachine(  968): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  968): handleMessage: X
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
D/WifiStateMachine(  968): handleMessage: E msg.what=131092
D/WifiStateMachine(  968): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  968): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
W/WifiStateTracker(  968): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  968): 
W/WifiStateTracker(  968):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  968):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
D/QcConnectivityService(  968): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  968): handleInetConditionChange: no active default network - ignore
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
D/WifiStateMachine(  968): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  968): transitionTo: destState=ConnectedState
D/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  968): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  968): handleMessage: X
V/WfdStateTracker( 1159): handleWifiStateChangedEvent: 1
,D/KeyguardUpdateMonitor( 1145): received broadcast android.net.wifi.STATE_CHANGE
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1145): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  968): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/ActivityManager(  968): Killing 4556:com.google.android.partnersetup/u0a9 (adj 15): empty #17
E/ActivityThread(  968): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  968): handleConnectivityChange: preConnState=2 connState=1
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
,E/Parcel  (  424): Reading a NULL string not supported here.
,D/LGDMClient( 2883): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/LGDMClient( 2883): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  968): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4880 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  264): RouteController
I/LGDMClient( 2883): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/        (  264): RouteController
E/LGDMClient( 2883): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2883): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2883): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/HyLog   ( 4880): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4880): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4880): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/LGDMClient( 2883): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/        (  264): RouteController
V/        (  264): RouteController
,D/LGDMSGCM( 4880): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4880): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/        (  264): RouteController
,D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,I/ActivityManager(  968): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4906 uid=10101 gids={50101, 1028, 1015, 3003}
,D/QCNEA   (  424): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  424): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  424): |CAC| updateNetCfgInfo
,V/QCNEA   (  424): |CAC| *********************************************
V/QCNEA   (  424): |CAC|                   Netconfig               
V/QCNEA   (  424): |CAC| *********************************************
V/QCNEA   (  424): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  424): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  424): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  424): |CAC| 	NetConfig: ip4        =192.168.1.145
V/QCNEA   (  424): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  424): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  424): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  424): |CAC| *********************************************
D/QCNEA   (  424): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  424): |CAC| net type = 1
V/QCNEA   (  424): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  424): |CAC| Received ssid= NG700
V/QCNEA   (  424): |CAC| 	ssid           =NG700
V/QCNEA   (  424): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  424): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  424): |CAC| *********************************************
D/QCNEA   (  424): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  424): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  424): |CAC| dispatchNetCfg: updating:0xb81bc8dc
,D/QCNEA   (  424): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/ActivityManager(  968): Killing 4584:com.lge.bnr/1000 (adj 15): empty #17
,I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4906): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4906): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4906): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CheckinService( 1965): Checking schedule, now: 1452773899671 next: 1452773844903
,I/CheckinService( 1965): active receiver: enabled
,I/NFS     ( 4906): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/CheckinService( 1965): Preparing to send checkin request
,I/EventLogService( 1965): Accumulating logs since 1452773812034
,I/Wireless_Storage( 4906): intf.getDisplayName() = rmnet_usb0
,I/Wireless_Storage( 4906): intf.getDisplayName() = lo
I/Wireless_Storage( 4906): intf.getDisplayName() = sit0
I/Wireless_Storage( 4906): intf.getDisplayName() = p2p0
I/Wireless_Storage( 4906): intf.getDisplayName() = teql0
I/Wireless_Storage( 4906): intf.getDisplayName() = wlan0
,D/NFS     ( 4906): interface name:wlan0 name:wlan0
D/NFS     ( 4906): addr:fe80::36fc:efff:fede:ae2%wlan0 broadcast:null
D/NFS     ( 4906): interface name:wlan0 name:wlan0
D/NFS     ( 4906): addr:192.168.1.145 broadcast:192.168.1.255
,I/Wireless_Storage( 4906): CONNECT : WIFI_CONNECT
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4920 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  968): Killing 4239:com.android.contacts/u0a21 (adj 15): empty #17
D/DhcpStateMachine(  968): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  968): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4920): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4920): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4920): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  968): GC_EXPLICIT freed 23577K, 49% free 29814K/57940K, paused 2ms+12ms, total 155ms
,D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
,W/GAV2    ( 4920): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1558): GC_EXPLICIT freed 1039K, 29% free 17827K/24832K, paused 2ms+3ms, total 25ms
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/WebViewChromium( 4920): Binding Chromium to the main looper Looper (main, tid 1) {42ac5398}
,I/chromium( 4920): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BrowserProcessMain( 4920): Initializing chromium process, renderers=0
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/chromium( 4920): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4920): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4920): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4920): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4920): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4920): Remote Branch: 
I/Adreno-EGL( 4920): Local Patches: 
I/Adreno-EGL( 4920): Reconstruct Branch: 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x43408990: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  968): battery changed pluggedType: 2
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4958 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4920): Starting up...
,D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,D/HyLog   ( 4958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4958): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4958): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  968): Killing 4255:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
W/dalvikvm( 4958): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4958): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4958): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4958): VFY: replacing opcode 0x62 at 0x005e
,D/QRemote ( 4775): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/MultiDex( 4958): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4958): install
,I/QRemote ( 4775): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/MultiDex( 4958): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4958): loading existing secondary dex files
,D/QRemote ( 4775): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/MultiDex( 4958): load found 3 secondary dex files
,I/QRemote ( 4775): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/MultiDex( 4958): install done
,D/QRemote ( 4775): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4775): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/PCSuite ( 4740): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4740): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4775): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4775): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,I/QRemote ( 4775): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4775): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
D/dalvikvm( 4958): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4958): VFY: unable to resolve instance field 61
,D/dalvikvm( 4958): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 4958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4958): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4958): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4958): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4958): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4958): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4958): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42acc728
,D/dalvikvm( 4958): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42acc728
,D/dalvikvm( 4958): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42acc728, skipping init
,D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42acc728
D/dalvikvm( 4958): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42acc728
,V/JNIHelp ( 4958): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42acc728
,D/dalvikvm( 4958): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42acc728
D/dalvikvm( 4958): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42acc728
,D/dalvikvm( 4958): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42acc728
,I/ProviderInstaller( 4958): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1558): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1558): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1558): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1965): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 1856): callingUid 10006, callindPid: 1856
,E/MDM     ( 1428): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/dalvikvm( 4958): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4958): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4958): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1965): Restart initialization of location
,I/dalvikvm( 4958): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4958): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4958): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/DrmWidevineDash(  271): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ff5000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1ff5000
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
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3536187817
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/wpa_supplicant( 2035): EAPOL: startWhen --> 0
,D/wpa_supplicant( 2035): EAPOL: disable timer tick
,D/dalvikvm( 4958): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42cb2f68
D/dalvikvm( 4958): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42cb2f68
,D/dalvikvm( 4958): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42cb2f68, skipping init
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/DhcpStateMachine(  968): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  968): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  968): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  968): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.145
V/LgDhcpStateMachineHelper(  968): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  968): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  968): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine(  968): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  968): RunningState
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  968): NetTransition Wakelock for ConnectedState released by timeout
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
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
D/WVCdm   (  271): PrepareKeyRequest: nonce=3785821912
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  968): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
D/WifiStateMachine(  968): processMsg: SupplicantStartedState
,D/WifiStateMachine(  968): processMsg: DefaultState
,D/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.145/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  968): send additional Connectivity Action
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
,D/WifiStateMachine(  968): handleMessage: X
,D/QcConnectivityService(  968): handleConnectivityChange:1 is conntected
D/LocSvc_java(  968): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  968): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  968): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1453): getPreferredApnId: subscription=0
D/QcConnectivityService(  968): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  968):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
E/QcConnectivityService(  968): Exception while trying to add src route: java.lang.NullPointerException
D/Nat464Xlat(  968): requiresClat: netType=1, hasIPv4Address=true
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4958): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5007): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
,D/dalvikvm( 4958): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4958): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 63ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Adreno-EGL( 4958): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4958): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4958): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4958): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4958): Remote Branch: 
I/Adreno-EGL( 4958): Local Patches: 
I/Adreno-EGL( 4958): Reconstruct Branch: 
,W/Settings( 4958): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4958): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4958): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4958): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4958): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4958): Remote Branch: 
I/Adreno-EGL( 4958): Local Patches: 
I/Adreno-EGL( 4958): Reconstruct Branch: 
,I/Adreno-EGL( 4958): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4958): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4958): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4958): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4958): Remote Branch: 
I/Adreno-EGL( 4958): Local Patches: 
I/Adreno-EGL( 4958): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/CheckinTask( 1965): Sending checkin request (11462 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/NotificationService(  968): updateLightListLocked :r=NotificationRecord(0x42beb3d0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  968): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/CheckinRequestBuilder( 1965): awaiting user notification for token
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,I/CheckinTask( 1965): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1965): Checking schedule, now: 1452773902073 next: 1453351298069
,I/CheckinService( 1965): active receiver: disabled
,D/GCM     ( 1558): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
E/Parcel  (  424): Reading a NULL string not supported here.
,E/Parcel  (  424): Reading a NULL string not supported here.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42ada510
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3018): start selecting data
,D/SIMObserver( 3018): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4045): begin check event
I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4045): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4045): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4045): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4045): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4045): handleAsyncCustNotification do not startCustService
,D/EAS     ( 4598): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4804): DownloadService onCreate
,D/EAS     ( 4598): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4598): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 4343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4343): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4343): networkInfo.isConnected() = false
,D/GCM     ( 1558): Connected
,I/DownloadManager( 4804): in removeSpuriousFiles
,V/DownloadManager( 4804): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2883): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4598): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMSGCM( 4880): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,W/ContextImpl( 4880): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
D/Tethering(  968): MasterInitialState.processMessage what=3
D/CaptivePortalTracker(  968): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b0c1a8 on behalf of 4804
I/NFS     ( 4906): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4906): CONNECT : WIFI_CONNECT
,I/DownloadManager( 4804): in trimDatabase
,V/DownloadManager( 4804): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b0dce8 on behalf of 4804
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2883): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4804): DownloadService onStartCommand
,D/GCM     ( 1558): Message class com.google.f.a.a.p
,I/LGDMClient( 2883): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,V/DownloadManager( 4804): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 2883): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LGDMClient( 2883): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b0fd50 on behalf of 4804
,D/LGDMClient( 2883): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2883): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,V/DownloadManager( 4804): DownloadService onDestroy
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42ada510
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3018): start selecting data
,D/SIMObserver( 3018): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4045): begin check event
,I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4804): DownloadService onCreate
,I/DownloadManager( 4804): in removeSpuriousFiles
V/DownloadManager( 4804): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/EAS     ( 4598): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4598): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b14228 on behalf of 4804
,I/DownloadManager( 4804): in trimDatabase
,V/DownloadManager( 4804): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4804): DownloadService onStartCommand
,V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b15e08 on behalf of 4804
I/LgeMiscReceiver( 4343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4343): action = android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 4598): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 4343): networkInfo.isConnected() = true
,D/PhoneState( 4343): setPdpRejectCasuse : false
,V/DownloadManager( 4804): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b17b40 on behalf of 4804
,D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2883): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4880): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4804): DownloadService onDestroy
,D/LGDMClient( 2883): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/NFS     ( 4906): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4906): CONNECT : WIFI_CONNECT
,I/LGDMClient( 2883): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4880): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
E/LGDMClient( 2883): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2883): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2883): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2883): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4677): Test app app.js loaded
I/jxcore-log( 4677): 
,I/Choreographer( 4677): Skipped 423 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4677): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  968): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4045): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
,D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42ada510
,D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4045): isOpenOperator : true
,D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3018): start selecting data
,D/SIMObserver( 3018): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4045): begin check event
,I/AppUp4:CustModeStarterReceiver( 4045): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/EAS     ( 4598): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4804): DownloadService onCreate
,D/EAS     ( 4598): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/LgeMiscReceiver( 4343): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4343): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4343): networkInfo.isConnected() = true
,D/PhoneState( 4343): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4837): onReceive CONNECTIVITY_CHANGE networkType=1
,D/LGDMClient( 2883): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/LGDMSGCM( 4880): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,I/DownloadManager( 4804): in removeSpuriousFiles
,V/DownloadManager( 4804): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/BatteryObserver( 1159): usb Uevent not necessary.
W/ContextImpl( 4880): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LGDMClient( 2883): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b1bcc8 on behalf of 4804
,I/LGDMClient( 2883): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/Settings( 4598): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NFS     ( 4906): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4906): CONNECT : WIFI_CONNECT
I/DownloadManager( 4804): in trimDatabase
,E/LGDMClient( 2883): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2883): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2883): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/DownloadManager( 4804): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b1d6c0 on behalf of 4804
I/LGDMClient( 2883): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
V/DownloadManager( 4804): DownloadService onStartCommand
,V/DownloadManager( 4804): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4804): created cursor android.database.sqlite.SQLiteCursor@42b1f870 on behalf of 4804
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  968): battery changed pluggedType: 2
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
V/DownloadManager( 4804): DownloadService onDestroy
D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  968): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,V/WifiServiceExtension(  968): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  968): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  968): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1221): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/GAV2    ( 4920): Thread[GAThread,5,main]: No campaign data found.
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  968): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,I/ActivityManager(  968): Killing 4616:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4275): [402] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4275): [1] 5.onFinished: Installation state replication succeeded.
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.450500 Y: -0.400375 Z: 9.812271 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450500 .y:-0.400375 .z:9.812271
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.442459 Y: -0.400543 Z: 9.805054 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.442459 .y:-0.400543 .z:9.805054
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  968):   Scheme: "sms"
,I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5115 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/SlideAside( 3773): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1493): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1493): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/SlideAside( 3773): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,I/[LGHome]LGPlusHomeDBManager( 1493): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
D/administrator(  968): Handling package changes for user 0
,I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  968): GC_EXPLICIT freed 2788K, 49% free 29885K/57940K, paused 3ms+8ms, total 105ms
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
D/HyLog   ( 5115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5115): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5115): I : /data/font/config/sfconfig.dat, No such file or directory (2)
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1221): Disconnected process message: 10
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/WifiController(  968): battery changed pluggedType: 2
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/Babel   ( 5115): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5115): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5115): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 5115): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5115): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
I/MediaCodecList( 5115): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5115): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5115): MmsConfig.loadFromDatabase
,I/[LGHome]EVENT( 1493): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5115): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 5115): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5115): MmsConfig.loadFromResources
,E/Babel   ( 5115): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5115): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,V/GmsNetworkLocationProvi( 1428): DISABLE
,W/Settings( 5115): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1428): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5115): [loadRssi] File not exist 
V/LGRssiData( 5115): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5115): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 5115): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5115): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5115): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:Utils( 4045): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 4045): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 4045): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4045): onReceive
,D/AppUp4:CustFacade( 4045): Context : android.app.ReceiverRestrictedContext@42ada510
D/AppUp4:CustFacade( 4045): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4045): isOpenOperator : true
D/AppUp4:CustFacade( 4045): isPhone : true
,I/LicenseContentProvider( 3018): start selecting data
,D/SIMObserver( 3018): simInfo1
,I/AppUp4:EulaManager( 4045): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4045): begin check event
D/AppUp4:Utils( 4045): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 4045): Event For Nothing, skip.
,D/LocationProviderProxy(  968): applying state to connected service
,D/LocationProviderProxy(  968): applying state to connected service
I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5166 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/HyLog   ( 5166): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5166): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5166): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/SystemConfig( 5166): BUILD Country: EU
,I/SystemConfig( 5166): BUILD Operator: OPEN
I/ActivityManager(  968): Killing 4740:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5182 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,I/SystemConfig( 5166): systemFeature RCS result false
,D/SystemConfig( 5166): refreshRcsSupport() :false
I/ActivityManager(  968): Killing 4775:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
,D/HyLog   ( 5182): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5182): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5182): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  968): Killing 4804:android.process.media/u0a23 (adj 15): empty #17
I/IcingCorporaProvider( 2680): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1965): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  968): Delaying start of: ServiceRecord{43664a38 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1965): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1965): GC_CONCURRENT freed 1889K, 22% free 19555K/24832K, paused 1ms+2ms, total 29ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2680): UpdateCorporaTask done [took 199 ms] updated apps [took 199 ms] 
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  968): battery changed pluggedType: 2
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/CaptivePortalTracker(  968): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  968): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  968): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  968): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  968): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  968): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  968): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  968): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/GAV4    ( 5115): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2035): nl80211: survey data missing!
,D/WifiStateMachine(  968): handleMessage: X
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,I/PowerManagerService(  968): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  968): [updateScreenState] screen on = false
D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  968): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  968): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,D/KnockOnPowerController(  968): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8138 usec
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
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.467041 Y: -0.399109 Z: 9.804596 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.467041 .y:-0.399109 .z:9.804596
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.438461 Y: -0.397293 Z: 9.818268 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438461 .y:-0.397293 .z:9.818268
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,I/Sensors (  322): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  968): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  968): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  968): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  968): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  968): proximitySensorChanged  positive = true
I/KnockOnPowerController(  968): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.441254 Y: -0.404953 Z: 9.825348 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.441254 .y:-0.404953 .z:9.825348
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.458176 Y: -0.419098 Z: 9.815079 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.458176 .y:-0.419098 .z:9.815079
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.453033 Y: -0.412827 Z: 9.804031 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.453033 .y:-0.412827 .z:9.804031
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.444397 Y: -0.401031 Z: 9.807602 
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444397 .y:-0.401031 .z:9.807602
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  968): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@432c32a0)
,D/KeyguardViewMediator( 1145): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1145): notifyScreenOnLocked
D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/KeyguardViewMediator( 1145): handleNotifyScreenOn
,D/KeyguardViewManager( 1145): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  968): **** SHOWN CALLED ****
I/WindowManager(  968): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb714f450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.446442 Y: -0.406342 Z: 9.815674 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.446442 .y:-0.406342 .z:9.815674
,D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/WifiStateMachine(  968): handleScreenStateChanged: true
,D/WifiStateMachine(  968): handleMessage: E msg.what=131154
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiNative-wlan0(  968): doString: SIGNAL_POLL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2035): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  968): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  968): stopMonitoring
,D/wpa_supplicant( 2035): nl80211: survey data missing!
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131127
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
,D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=132097
D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  968): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 2035): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 2035): initialize kt scan interval and do scan state=9
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
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1159): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43604d00 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1159): enqueuing start. mLedList.size()=2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1159): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3773): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,D/WeatherAncestor( 1847): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:18:41
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,I/SlideAside( 3773): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/UpdateThreadPoolManager( 1847): 2 : This is isUpdating : false
,D/WeatherAncestor( 1847): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:18:41
,D/WeatherService( 1847): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.459595 Y: -0.391479 Z: 9.790024 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459595 .y:-0.391479 .z:9.790024
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  968): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.449493 Y: -0.389709 Z: 9.820587 
V/qcom_sensors_hal(  968): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  968): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  968): hal_process_report_ind: X: -0.436188 Y: -0.400803 Z: 9.805054 
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.449493 .y:-0.389709 .z:9.820587
D/qcom_sensors_hal(  968): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=0
D/qdlights( 1159): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1159): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1159): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1159): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1159): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1159): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1159): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1159): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1159): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1159): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1159): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 195, B = 195
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  968): Excessive delay in blankDisplay() while turning screen off: 420ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1159): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1159): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 177, B = 177
,D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452773922291, nextTick: 17741, mDrawingTime: 0
D/qdlights( 1159): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1159): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 165, B = 165
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452773922312, nextTick: 17721, mDrawingTime: 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1159): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 159, B = 159
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/qdlights( 1159): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 153, B = 153
,D/WeatherService( 1847): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:18:42
,D/WeatherService( 1847): 2 : ACTION screen on
,D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1847): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:18:42
D/qdlights( 1159): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 147, B = 147
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/qdlights( 1159): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 141, B = 141
,V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
,E/Parcel  (  424): Reading a NULL string not supported here.
,D/GsmSST  ( 1453): Emergency Service
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1453): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/qdlights( 1159): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 135, B = 135
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1453): [PhoneIntfMgr] sigLevel = 5
,V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_ON
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_ON
,D/qdlights( 1159): set_light_notifications: 2,ff008181,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 129, B = 129
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  968): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  968): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  968): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1145): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1145): notifyScreenOffLocked
,D/qdlights( 1159): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 123, B = 123
D/qcom_sensors_hal(  968): hal_acquire_resources
D/qcom_sensors_hal(  968): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  968): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  968): hal_wait_for_response: timeout=1000
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,V/qcom_sensors_hal(  968): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  968): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  968): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  968): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1159): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 117, B = 117
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1159): usb Uevent not necessary.
,D/qdlights( 1159): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 111, B = 111
W/ProcessCpuTracker(  968): Skipping unknown process pid 5234
W/ProcessCpuTracker(  968): Skipping unknown process pid 5235
W/ProcessCpuTracker(  968): Skipping unknown process pid 5237
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ProcessCpuTracker(  968): Skipping unknown process pid 5245
W/ProcessCpuTracker(  968): Skipping unknown process pid 5247
,W/ProcessCpuTracker(  968): Skipping unknown process pid 5251
D/qdlights( 1159): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 105, B = 105
,D/KeyguardViewMediator( 1145): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3} (stop requested)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/ActivityManager(  968): Moving to DESTROYING: ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
D/qdlights( 1159): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 99, B = 99
I/LGImmersionVibrator(  968): Vibrator off
D/UsbSettings( 2613): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2613): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiStateMachine(  968): handleScreenStateChanged: false
D/WifiStateMachine(  968): handleMessage: E msg.what=131154
,D/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): handleMessage: X
D/WifiStateMachine(  968): handleMessage: E msg.what=131158
D/WifiStateMachine(  968): processMsg: ConnectedState
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3} (stop complete)
,D/WifiController(  968): battery changed pluggedType: 2
D/WifiStateMachine(  968): processMsg: L2ConnectedState
D/WifiStateMachine(  968): processMsg: ConnectModeState
D/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiStateMachine(  968): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  968): doBoolean: DRIVER SETSUSPENDMODE 1
D/qdlights( 1159): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 93, B = 93
,E/AudioSystem(  968): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 968
D/KeyguardViewMediator( 1145): handleNotifyScreenOff
,D/KeyguardViewManager( 1145): onScreenTurnedOff()
D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
D/wpa_supplicant( 2035): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 2035): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 280 plugged : true isCharging : false
V/SRS_Proc(  271): ParamSet string: screen_state=off
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  968): CMD_SCREEN_OFF 
D/WifiController(  968): shouldWifiStayAwake TRUE
D/qdlights( 1159): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 87, B = 87
,E/CliptrayService( 1159): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1159): getCurrentHighestLGLedRecord() start. mLedList.size=3
V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{42e2f2f0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{435b6228 stackId=1, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/VolumeVibrator( 1159): clear
D/wpa_supplicant( 2035): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  968):    returned true
D/WifiStateMachine(  968): handleMessage: X
D/qdlights( 1159): set_light_notifications: 2,ff005151,10,0,2
D/qdlights( 1159): [Current] = 255, R = 0, G = 81, B = 81
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
,I/[LGHome]EVENT( 1493): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1159): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 75, B = 75
,E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
E/Parcel  (  424): Reading a NULL string not supported here.
D/WeatherService( 1847): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:18:42
,D/WeatherService( 1847): 2 : ACTION screen off
V/TelephonyAutoProfiling(  968): [getValue] FEATURE key : trf_based_vzw, value : null
D/WeatherService( 1847): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:18:42
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
,D/BubblePopupHelper( 1145): isShowingBubblePopup : false
D/qdlights( 1159): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 69, B = 69
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1453): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1453): Emergency Service
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1453): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1453): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1453): Action intent recieved:android.intent.action.SCREEN_OFF
D/qdlights( 1159): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 63, B = 63
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/NfcService( 1475): NFC-C OFF
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_OFF
D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1465): [TangibleIO] LCD is off. Remove tangible if exist.
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/qdlights( 1159): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1159): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 51, B = 51
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1159): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1159): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1159): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1159): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 21, B = 21
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1159): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1159): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1159): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1159): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1159): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 279 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Sensors (  322): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,D/WifiStateMachine(  968): handleMessage: E msg.what=131155
,D/WifiStateMachine(  968): processMsg: ConnectedState
,D/WifiStateMachine(  968): processMsg: L2ConnectedState
,D/WifiStateMachine(  968): handleMessage: X
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1145): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1145): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1145): OMADM Lock is OFF
,D/KeyguardViewMediator( 1145): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1145): doKeyguard is called, but is not locked.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Procstats( 1965): User is not opted-in to Usage & Diagnostics.
,D/Diskstats( 1965): User is not opted-in to Usage & Diagnostics.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452773940041, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452773940053, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452773940548252346; DSPS: 5271712; Offset: 1452773779668369534
,D/Netstats( 1965): User is not opted-in to Usage & Diagnostics.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/PerfProfileCollectorService( 1965): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1965): removeStateFiles() called
,D/PerfProfileCollectorService( 1965): User is not opt-in to Usage & Diagnostics.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452773960550181869; DSPS: 5927135; Offset: 1452773779668376450
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452773980552029569; DSPS: 6582556; Offset: 1452773779668362577
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/WifiController(  968): battery changed pluggedType: 2
D/HeadsetStateMachine( 1221): Disconnected process message: 10
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1159): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
D/WifiController(  968): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/wpa_supplicant( 2035): wlan0: BSS: Remove id 8 BSSID fc:94:e3:11:35:3a SSID 'UPC0039325' due to wpa_bss_flush_by_age
D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2035): wlan0: BSS: Remove id 9 BSSID fe:94:e3:11:35:3c SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 2035): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 fc:94:e3:11:35:3a]
,D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 fe:94:e3:11:35:3c]
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452774000028, nextTick: 60000, mDrawingTime: 3
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452774000063, nextTick: 59968, mDrawingTime: 1
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452774000553950344; DSPS: 7237979; Offset: 1452773779668360745
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452774020555530493; DSPS: 7893391; Offset: 1452773779668353980
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  968): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 276 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1145): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1221): Disconnected process message: 10
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1145): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1465): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetTangibleController( 1465): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1465): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/OtgUmsTangibleController( 1465): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm( 1159): GC_CONCURRENT freed 2879K, 11% free 25450K/28508K, paused 43ms+2ms, total 100ms
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452774040557049079; DSPS: 8548800; Offset: 1452773779668377204
,D/KeyguardUpdateMonitor( 1145): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1145): handleTimeUpdate
,D/KeyguardModel( 1145): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452774060045, nextTick: 59978, mDrawingTime: 4
,D/Clock   ( 1145): Clock updated, drawingStartTime : 1452774060052, nextTick: 59975, mDrawingTime: 2
,D/qcom_sensors_hal(  968): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  968): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  968): hal_ts_offset_is: Apps: 1452774060558688134; DSPS: 9204214; Offset: 1452773779668368310
,I/jxcore-log( 4677): --= Surplus to requirements =--
I/jxcore-log( 4677): 
,I/jxcore-log( 4677): ****TEST TOOK:  ms ****
I/jxcore-log( 4677): 
,I/jxcore-log( 4677): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4677): 
,D/AndroidRuntime( 5493): 
D/AndroidRuntime( 5493): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5493): CheckJNI is OFF
,D/dalvikvm( 5493): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5493): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5493): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5493): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5493): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 5493): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,E/memtrack( 5493): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5493): failed to load memtrack module: -2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/AndroidRuntime( 5493): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  968): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
,I/ActivityManager(  968): Killing 4677:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
,I/MDM     (  968):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  968):   Force finishing activity ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  968): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  968): moveHomeStack:
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e954a0 stackId=0, 1 tasks}
,V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  968): resumeTopActivityLocked: Resumed ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e954a0 stackId=0, 1 tasks}
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: some activity pausing.
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{4512c6d8 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e954a0 stackId=0, 1 tasks}
,D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
I/WindowState(  968): WIN DEATH: Window{452703b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  968): Client connection lost with reason: 4
,D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1493): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1493): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1493): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1493): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,D/PhoneApp( 1453): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1493): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1493): [Launcher.java:868:onResume()]onResume end
,I/[LGHome]EVENT( 1493): [Launcher.java:894:onPause()]onPause
,D/WeatherAncestor( 1847): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:21:19
,D/UpdateThreadPoolManager( 1847): 2 : This is isUpdating : false
,D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
,D/WeatherAncestor( 1847): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:21:19
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
,V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
D/WeatherService( 1847): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherService( 1847): 2 : shouldTimeTickRegistered : false
,I/[LGHome]EVENT( 1493): [Launcher.java:4955:onStop()]onStop
,I/[LGHome]EVENT( 1493): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/InputMethodManagerService(  968): IME STATUS OFF
,W/Binder  ( 1317): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1317): java.lang.NullPointerException
W/Binder  ( 1317): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1317): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1317): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1317): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 4677 uid 10304
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/PackageSettings(  968): Skipping PackageSetting{42f9da50 com.example.hello/10312} due to missing metadata
,I/ActivityManager(  968): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e954a0 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1145): GC_CONCURRENT freed 7827K, 11% free 70569K/78580K, paused 4ms+5ms, total 48ms
,D/dalvikvm( 1145): WAIT_FOR_CONCURRENT_GC blocked 45ms
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3773): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,I/SlideAside( 3773): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
,I/[LGHome]EVENT( 1493): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1493): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1493): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]Launcher.Model( 1493): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/System.err( 2668): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 2668): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2668): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2668): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2668): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2668): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2668): 	at android.os.Looper.loop(Looper.java:136)
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
W/System.err( 2668): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2668): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2668): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2668): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
,W/System.err( 2668): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2668): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{42f431b0 u0 com.lge.launcher2/.Launcher t1} time:295736
,D/dalvikvm( 2680): GC_EXPLICIT freed 4348K, 27% free 18154K/24832K, paused 1ms+48ms, total 99ms
,D/AppUp4:Utils( 4045): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 4045): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
,I/AppUp4  ( 4045):  isExcludedPackage  packagename = com.test.thalitest
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
,D/AppUp4  ( 4045):  isExcludedPackage TRUE : com.test.thalitest
,W/GeofencerStateMachine( 1428): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,D/dalvikvm(  968): GC_EXPLICIT freed 2407K, 49% free 29947K/57940K, paused 4ms+9ms, total 129ms
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
D/KeyguardModel( 1145): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "sms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  968): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5526 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
,W/ActivityManager(  968): getAssistContextExtras failed: no resumed activity
,D/administrator(  968): Handling package changes for user 0
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "smsto"
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,D/GlobalAccess( 1145): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1145): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1145): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mms"
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm( 1493): GC_CONCURRENT freed 5611K, 9% free 60857K/66648K, paused 1ms+3ms, total 25ms
I/PackageManager(  968):   Action: "android.intent.action.SENDTO"
I/PackageManager(  968):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  968):   Scheme: "mmsto"
,D/dalvikvm( 1493): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/PackageManager(  968): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  968): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5538 uid=10090 gids={50090}
,D/HyLog   ( 5526): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5526): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5526): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5538): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/[BNRAppListMgrReceiver]( 5526): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
D/BackupManagerService(  968): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  968): removePackageParticipantsLocked: uid=10304 #1
,I/InteractionManagerConfigurator(  968): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  968): com.test.thalitest isn't inclued in dragdropPackageList
,I/LockScreenSettings( 5538): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/ActivityManager(  968): Killing 4598:com.lge.email/u0a24 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e954a0 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/VoicemailCleanupService( 1807): Cleaning up data for package: com.test.thalitest
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1493): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
D/KeyguardModel( 1145): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1145): createShortcutInfo...
I/[LGHome]Launcher.Model( 1493): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/ActivityManager(  968): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5552 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1145): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1145): createShortcutInfo...
I/[LGHome]Launcher.Model( 1493): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1145): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1145): createShortcutInfo...
I/[LGHome]LauncherAppWidgetHostView( 1493): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
D/KeyguardModel( 1145): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1145): createShortcutInfo...
I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
D/KeyguardModel( 1145): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 1493): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1493): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
D/KeyguardModel( 1145): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1145): createShortcutInfo...
D/KeyguardModel( 1145): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1145): createShortcutInfo...
I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1145): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1145): createShortcutInfo...
,D/KeyguardModel( 1145): handleShortcutListChanged...
,I/ActivityManager(  968): Killing 4837:com.google.android.setupwizard/u0a52 (adj 15): empty #17
I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e954a0 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
D/dalvikvm(  968): GC_EXPLICIT freed 648K, 49% free 29913K/57940K, paused 4ms+14ms, total 210ms
D/HyLog   ( 5552): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5552): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5552): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/LGEmail ( 5552): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5552): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:null]
,E/LGEmail ( 5552): Email Not Started (at LGEmailContentProvider.java query 509)[v:null]
I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1493): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,E/[LGHome]NumberBadge( 1493): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]EVENT( 1493): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/LGEmail ( 5552): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1493): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/AndroidRuntime( 5493): Shutting down VM
I/[LGHome]EVENT( 1493): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,I/[LGHome]Launcher( 1493): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/dalvikvm( 5493): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,I/ActivityManager( 1493): Timeline: Activity_idle id: android.os.BinderProxy@42ac0f60 time:296095
,W/BaseRuntimeLoader( 5552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5552): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5552): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/PackageChangeReceiver( 5552): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/PackageIntentReceiver( 2613): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 2613): Receive package name : com.test.thalitest
,I/ActivityManager(  968): Killing 4851:com.android.chrome/u0a63 (adj 15): empty #17
D/HideNavigationAppsReceiver( 2613): Delete mPackageMame : com.test.thalitest
,I/IcingCorporaProvider( 2680): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  968): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5574 uid=10073 gids={50073, 3003, 1028, 1015}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e954a0 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5574): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5574): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5574): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/IcingCorporaProvider( 2680): UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SQLiteDatabase( 5574): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 5574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 5574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5574): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5574): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5574): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5574): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5574): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5574): 	at aJh.a(Scopes.java:65)
E/SQLiteDatabase( 5574): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5574): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteDatabase( 5574): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteDatabase( 5574): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5574): 	at aGr.a(GellyInjector.java:117)
E/SQLiteDatabase( 5574): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5574): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteDatabase( 5574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteDatabase( 5574): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 5574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteDatabase( 5574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5574): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5574): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteDatabase( 5574): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5574): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteDatabase( 5574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteDatabase( 5574): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5574): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 5574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteOpenHelper( 5574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5574): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5574): 	at Bi.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5574): 	at Bu.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5574): 	at Bu.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5574): 	at aGG.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5574): 	at aJh.a(Scopes.java:65)
E/SQLiteOpenHelper( 5574): 	at aGM.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5574): 	at fx.a(GellyInjectorStore.java:194)
E/SQLiteOpenHelper( 5574): 	at fx.a(GellyInjectorStore.java:510)
E/SQLiteOpenHelper( 5574): 	at aGI.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5574): 	at aGr.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5574): 	at Tg.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5574): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5574): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1007)
E/SQLiteOpenHelper( 5574): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4417)
E/SQLiteOpenHelper( 5574): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 5574): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1260)
E/SQLiteOpenHelper( 5574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5574): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 5574): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/SQLiteOpenHelper( 5574): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5574): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5574): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/SQLiteOpenHelper( 5574): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/SQLiteOpenHelper( 5574): 	at dalvik.system.NativeStart.main(Native Method)

```
